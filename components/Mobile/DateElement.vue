<template>
  <div class="chat-wrapper d-flex flex-column" style="height: 100%">
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
    <div class="text-white scroll" style="flex: 1; padding: 0px 27px 10px 27px">
      <MainHomeDates />
      <MainHomeDates />
      <MainHomeDates />
    </div>
    <div class="mobile-line text-white"></div>
    <div class="" style="padding: 0px 20px 10px 20px">
      <div style="padding: 15px 27px 0 27px">
        <MainHomeSidebarFooter />
      </div>
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
        {
          href: "/css/home.css",
          rel: "stylesheet",
        },
      ],
    });
  },
};
</script>
