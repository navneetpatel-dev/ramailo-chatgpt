<template>
  <div class="chat-wrapper d-flex flex-column" style="height: 100%">
    <!-- Chat button -->
    <div class="new-chat">
      <button
        type="button"
        class="btn btn-outline-light w-100"
        style="background-color: #2f2a2a"
      >
        + New Chat
      </button>
      <span class="text-white rounded-3 arrow-down">
        <img src="/images/arrow-down.png" alt="" />
      </span>
    </div>
    <div class="mobile-line text-white"></div>
    <!-- Question Answers -->
    <div class="question-answer-layout" style="flex: 1">
      <MobileQuestion />
      <MobileAnswer />
      <MobileQuestion />
      <MobileAnswer />
    </div>
    <!-- Question Input -->
    <div class="" style="padding: 0px 20px 10px 20px">
      <MobileQuestionInput />
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    useHead({
      link: [
        {
          href: "/css/mobile/home.css",
          rel: "stylesheet",
        },
      ],
    });
  },
};
</script>
