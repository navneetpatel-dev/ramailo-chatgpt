<template>
  <div>Hello Home</div>
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
