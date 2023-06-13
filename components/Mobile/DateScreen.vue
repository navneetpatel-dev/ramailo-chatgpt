<template>
  <div class="mobile-wrapper container-fluid g-0">
    <div class="message-icon">
      <img src="/images/message-icon.png" alt="" />
    </div>
    <div class="login">
      <div class="" style="height: 100%; background-color: #2f2a2a">
        <!-- Login elements component here -->
        <MobileDateElement />
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
          href: "/css/mobile/login.css",
          rel: "stylesheet",
        },
      ],
    });
  },
};
</script>
