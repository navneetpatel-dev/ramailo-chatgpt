<template>
  <div class="input-container">
    <div style="margin-top: 14px; position: relative">
      <input
        type="email"
        class="form-control rounded-1"
        id="exampleFormControlInput1"
        placeholder="Ask a question..."
        style="height: 70px; background-color: #d9d9d9"
      />
      <div
        class="d-flex justify-content-center align-items-center"
        style="position: absolute; top: 25px; right: 20px"
      >
        <img src="/images/send.png" alt="" />
      </div>
    </div>
    <p
      class="text-left"
      style="
        font-size: 12px;
        font-weight: 400;
        margin-top: 12px;
        color: #dadada;
      "
    >
      Sample text area with a
      <span style="text-decoration: underline">link</span>, which can be used to
      redirect the user to helpful section or other content of the chat bot.
    </p>
  </div>
</template>
