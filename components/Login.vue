<template>
  <div
    class="d-flex justify-content-center align-items-center mx-auto login-container"
  >
    <div>
      <h1 class="text-center" style="display: block; font-size: 34px">
        Heading Placeholder to be used for more description about the CHAT bot.
        <!-- Heading -->
      </h1>
      <div class="mx-auto form-heading">
        <p class="text-center form-para">Login to Chat with WAL-AI</p>
        <div class="mb-3">
          <input
            type="email"
            class="form-control rounded-1 inputfield"
            id="exampleFormControlInput1"
            placeholder="Email Address"
          />
        </div>
        <div class="mb-3">
          <input
            type="email"
            class="form-control rounded-1 inputfield"
            id="exampleFormControlInput1"
            placeholder="First Name"
          />
        </div>
        <button type="button" class="btn w-100 text-light loginbutton">
          Login
        </button>
        <p class="text-center registeredpara">
          Only registered user can login to WAL-AI. Please contact the
          administrator to get your access.
        </p>
      </div>
    </div>
  </div>
  <LoginFooter />
</template>
