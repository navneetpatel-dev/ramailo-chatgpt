<template>
  <div class="parent container-fluid g-0">
    <!-- SIDEBAR -->
    <div class="sidebar d-flex flex-column">
      <MainHomeNewChatButton />
      <MainHomeDates />
      <div class="line" style="position: absolute"></div>
      <MainHomeSidebarFooter />
    </div>
    <!-- QUERIES -->
    <div class="queries">
      <div class="wrapper">
        <div class="question-answer">
          <MainHomeQuestion />
          <MainHomeAnswer />
          <MainHomeQuestion />
          <MainHomeAnswer />
        </div>
        <MainHomeQuestionInput />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    useHead({
      link: [
        {
          href: "/css/home.css",
          rel: "stylesheet",
        },
      ],
    });
  },
};
</script>
