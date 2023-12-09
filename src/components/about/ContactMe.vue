<script setup></script>

<template>
  <div class="contact_wrapper">
    <div class="contact_left">
      <h1>contact</h1>
      <img
        src="https://drive.google.com/uc?export=view&id=1v6ie3kY2RaheaAvzpVS1b3PxrlKLuRA7"
        alt=""
      />
    </div>

    <form
      class="contact_container"
      action="https://formsubmit.co/spacebunnybun00@gmail.com"
      method="POST"
    >
      <label for="fullName">Full Name</label>
      <input type="text" id="fullName" name="fullName" required />

      <label for="email">E-mail</label>
      <input type="email" id="email" name="email" required />

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="4" required></textarea>

      <button type="submit">Submit</button>
      <input type="hidden" name="_next" value="" />
      <input type="hidden" name="_captcha" value="false" />
    </form>
  </div>
</template>

<style scoped>
.contact_wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-transform: uppercase;
}

.contact_left h1 {
  font-size: 5rem;
}

.contact_container {
  text-transform: uppercase;
  width: 60%;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

button {
  text-transform: uppercase;
}

img {
  width: 40%;
}
</style>
