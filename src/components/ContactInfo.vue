<template>
  <section id="contact-section">
    <div class="container-contact">
      <div class="contact">
        <h1>Contact</h1>
        <p>Looking forward to hearing from you!</p>
        <br />
        <h3>Phone</h3>
        <p>0744-750-373</p>
        <h3>Email</h3>
        <p>serbandavid83@yahoo.com</p>
      </div>
      <form>
        <div class="fields">
          <div class="first-name">
            <label for="first-name">First Name</label>
            <input type="text" />
          </div>
          <div class="last-name">
            <label for="last-name">Last Name</label>
            <input type="text" />
          </div>
          <div class="email">
            <label for="email">Email</label>
            <input type="email" />
          </div>
          <div class="subject">
            <label for="subject">Subject</label>
            <input type="text" />
          </div>
          <div class="message">
            <label for="message">Message</label>
            <textarea
              name="message"
              id="message"
              cols="35"
              rows="10"
            ></textarea>
          </div>
          <button class="submit">Submit</button>
        </div>
      </form>
    </div>
  </section>
</template>

<style scoped>
#contact-section {
  height: 77vh;
  margin-top: 5.5rem;
}

h1 {
  font-size: 2.5rem;
}

p {
  margin-bottom: 1rem;
}

label {
  display: block;
  padding: 0.5rem 0;
}

input {
  background-color: transparent;
  border: 1px solid #000;
  width: 14rem;
  height: 2.5rem;
  padding: 0 0.5rem;
  margin-bottom: 0.5rem;
}

textarea {
  background-color: transparent;
  border: 1px solid #000;
  padding: 0.5rem 0.5rem;
}

.container-contact {
  display: grid;
  grid-template-columns: 2fr 1fr;
  max-width: 1100px;
  margin: auto;
  margin-top: 4rem;
  padding: 0 1rem 4rem 1rem;
}

.contact {
  padding-right: 2rem;
}

.fields {
  display: grid;
  grid-template-areas:
    'first-name last-name'
    'email subject'
    'message submit';
}

.first-name {
  grid-area: first-name;
}

.last-name {
  grid-area: last-name;
}

.email {
  grid-area: email;
}

.message {
  grid-area: message;
}

.submit {
  grid-area: submit;
}

.submit {
  cursor: pointer;
  display: inline-block;
  font-size: 1.3rem;
  font-weight: 700;
  height: 9.5rem;
  width: 10rem;
  margin-top: 2.9rem;
  margin-left: 2rem;
  border: 1px solid #fff;
  background-color: #ffa500;
  border-radius: 50%;
  color: #fff;
  transition: all 0.5s;
}

.submit:hover {
  background-color: #f4f4f4;
  color: #000;
  border: 1px solid #000;
}

.message {
  margin-bottom: 10rem;
}
</style>
