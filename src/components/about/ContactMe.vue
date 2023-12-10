<script setup></script>

<template>
  <div class="all_container">
    <div class="contact_wrapper">
      <div class="contact_left">
        <h1>contact</h1>
        <img
          class="image"
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
        <input type="text" id="name" name="name" required />

        <label for="email">E-mail</label>
        <input type="email" name="email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Submit</button>
        <input
          type="hidden"
          name="_next"
          value="https://ashley-gomez.vercel.app/about"
        />
        <input type="hidden" name="_captcha" value="false" />
        <img
          class="image2"
          src="https://drive.google.com/uc?export=view&id=1v6ie3kY2RaheaAvzpVS1b3PxrlKLuRA7"
          alt=""
        />
      </form>
    </div>
  </div>
</template>

<style scoped>
.image2 {
  display: none;
}
button {
  color: var(--color-pink);
  background-color: white;
  cursor: pointer;
}
.contact_wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-transform: uppercase;
  background-color: var(--color-pink);
  color: white;
  width: 70%;
}
input,
textarea {
  text-transform: uppercase;
  border-radius: 15px;
  border-width: 0;
  width: 500px;
  height: 10px;
  padding: 10px;
}

textarea {
  height: 100px;
}

:focus {
  outline: 4px solid var(--color-darkpink);
  border-radius: 15px;
}

.all_container {
  background-color: var(--color-pink);
  width: 100%;
  display: flex;
  justify-content: center;
  height: 550px;
  align-items: end;
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
.contact_container button {
  justify-self: center;
  margin-left: auto;
  margin-right: auto;
}

button {
  text-transform: uppercase;
}

img {
  width: 50%;
}
.contact_left {
  display: flex;
  gap: 30px;
  flex-direction: column;
  justify-content: center;
}
@media screen and (max-width: 1700px) {
  img {
    width: 60%;
  }
}

@media screen and (max-width: 1600px) {
  .contact_wrapper {
    gap: 50px;
    width: 75%;
  }
  img {
    width: 70%;
  }
}

@media screen and (max-width: 1500px) {
  .contact_wrapper {
    gap: 30px;
    width: 70%;
  }
  img {
    width: 70%;
  }
}
@media screen and (max-width: 800px) {
  .image2 {
    display: flex;
    width: 80%;
  }
  .image {
    display: none;
  }
  .all_container {
    display: flex;
    height: 900px;
    width: 100%;
    justify-content: center;
  }
  .contact_wrapper {
    flex-direction: column;
    justify-content: center;
    gap: 30px;
  }
  .contact_container {
    width: 80%;
    justify-content: center;
  }

  input,
  textarea {
    width: 400px;
    height: 10px;
    padding: 10px;
  }
  label {
    font-size: 0.8rem;
  }

  textarea {
    height: 100px;
  }
  .contact_left h1 {
    font-size: 4rem;
  }
}

@media screen and (max-width: 500px) {
  .image2 {
    display: flex;
    width: 80%;
  }
  .image {
    display: none;
  }
  .all_container {
    display: flex;
    height: 750px;
    width: 100%;
    justify-content: center;
  }
  .contact_wrapper {
    flex-direction: column;
    justify-content: center;
    gap: 30px;
  }
  .contact_container {
    width: 80%;
    justify-content: center;
  }

  input,
  textarea {
    width: 230px;
    height: 10px;
    padding: 10px;
  }
  label {
    font-size: 0.7rem;
  }

  textarea {
    height: 100px;
  }
  .contact_left h1 {
    font-size: 3rem;
  }
}
@media screen and (max-width: 320px) {
  .contact_left h1 {
    font-size: 2rem;
  }
  input,
  textarea {
    width: 170px;
    padding: 10px;
  }
  textarea {
    height: 30px;
  }
  .contact_container {
    width: 90%;
  }
  .all_container {
    height: 600px;
  }
  label {
    font-size: 0.6rem;
  }
}
</style>
