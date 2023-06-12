<template>
  <div
    class="d-flex justify-content-center align-items-center mx-auto"
    style="
      max-height: 100vh;
      min-height: 100vh;
      max-width: 673px;
      min-width: 673;
    "
  >
    <div>
      <h1 class="text-center" style="display: block; font-size: 34px">
        Heading Placeholder to be used for more description about the CHAT bot.
        <!-- Heading -->
      </h1>
      <div
        class="mx-auto"
        style="margin-top: 90px; max-width: 367px; width: 367px"
      >
        <p class="text-center" style="font-weight: 400">
          Login to Chat with WAL-AI
        </p>
        <div class="mb-3">
          <input
            type="email"
            class="form-control rounded-1"
            id="exampleFormControlInput1"
            placeholder="Email Address"
            style="height: 50px; background-color: #ecebeb"
          />
        </div>
        <div class="mb-3">
          <input
            type="email"
            class="form-control rounded-1"
            id="exampleFormControlInput1"
            placeholder="First Name"
            style="height: 50px; background-color: #ecebeb"
          />
        </div>
        <button
          type="button"
          class="btn w-100 text-light"
          style="background-color: #f32e33; height: 67px"
        >
          Login
        </button>
        <p
          class="text-center"
          style="
            color: #afafaf;
            font-size: 14px;
            font-weight: 400;
            margin-top: 12px;
          "
        >
          Only registered user can login to WAL-AI. Please contact the
          administrator to get your access.
        </p>
      </div>
    </div>
  </div>
  <LoginFooter />
</template>
