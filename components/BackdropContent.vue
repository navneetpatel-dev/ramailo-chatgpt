<template>
  <div class="modal-wrapper">
    <h1>Welcome to WAL-AI</h1>
    <p class="para">
      This is the area where Lorem ipsum dolor sit amet, consectetur adipiscing
      elit. Mauris tincidunt rutrum neque, sit amet ornare nulla bibendum sit
      amet. Vestibulum at lorem vel massa iaculis finibus vel et justo.
      Vestibulum efficitur dui sed mauris vehicula, placerat vulputate purus
      aliquam.
    </p>
    <div class="sub-heading">
      <div class="first">
        <img src="/images/image1.jpg" alt="" />
        <div>
          <h6>Sub heading</h6>
          <p>
            Sub Heading.. This is the area where Lorem ipsum dolor sit amet,
            consectetur adipiscing elit. Mauris tincidunt rutrum neque, sit amet
            ornare nulla bibendum...
          </p>
        </div>
      </div>
      <div class="second">
        <img src="/images/image2.png" alt="" />
        <div>
          <h6>Sub heading</h6>
          <p>
            Sub Heading.. This is the area where Lorem ipsum dolor sit amet,
            consectetur adipiscing elit. Mauris tincidunt rutrum neque, sit amet
            ornare nulla bibendum...
          </p>
        </div>
      </div>
    </div>
    <div class="my-btn d-flex justify-content-center">
      <button
        type="button"
        class="btn text-light"
        style="background-color: #f32e33; height: 67px; width: 280px"
      >
        Continue
      </button>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    useHead({
      link: [
        {
          href: "/css/backdrop-content.css",
          rel: "stylesheet",
        },
      ],
    });
  },
};
</script>
