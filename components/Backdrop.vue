<template>
  <div class="backdrop">
    <div class="custom-modal">
      <BackdropContent />
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    useHead({
      link: [
        {
          href: "/css/backdrop.css",
          rel: "stylesheet",
        },
      ],
    });
  },
};
</script>
