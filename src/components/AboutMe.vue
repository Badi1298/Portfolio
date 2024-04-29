<template>
  <div class="header-container">
    <img src="../img/portrait.jpg" alt="me" />
    <div class="description">
      <h1>Hello</h1>
      <h3>A Little About Me</h3>
      <p>
        I am a passionate 25 year old, self-taught programmer, constantly
        looking for ways to better myself and my craft.
        <br />
        I started this journey after taking a gap year in my 5th year at the
        University of Medicine, Science and Technology, "George Emil Palade",
        Targu Mures. In the span of 6 months I studied intensively and succeded
        in getting a job as a front-end developer. From then until now I have
        been hard at work, learning and gaining experience, not only from my
        job, but also by continuing to learn from online resources.
        <br />
        I take pride in my work ethic, attention to detail and dedication. I
        enjoy working in a team and finding the best solutions together, through
        communication and collaboration.
      </p>
      <ul>
        <li><router-link class="orange" to="/resume">Resume</router-link></li>
        <li><router-link class="red" to="/projects">Projects</router-link></li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Oxygen:wght@700&display=swap');

.header-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  max-width: 1100px;
  height: 61vh;
  margin: 5rem auto 16rem;
  justify-content: center;
  align-items: center;
  text-align: left;
}

img {
  width: 500px;
  height: 500px;
  object-fit: cover;
  border-radius: 100%;
}

.description {
  display: flex;
  flex-direction: column;
}

h1 {
  font-family: 'Oxygen', sans-serif;
  font-size: 6rem;
  margin-bottom: 1.5rem;
  padding: 0 2rem;
}

h3 {
  padding: 0.3rem 2rem;
}

p {
  padding: 0.5rem 2rem;
  margin-bottom: 3rem;
}

ul {
  display: flex;
  list-style: none;
  align-items: center;
  justify-content: center;
  margin-bottom: 4rem;
}

ul li {
  margin-top: 3rem;
}

ul li a {
  font-size: 1.3rem;
  font-weight: 700;
  padding: 3.7rem 2.2rem;
  margin: 0 2rem;
  border: 1px solid #fff;
  border-radius: 50%;
  color: #fff;
  transition: all 0.5s;
}

a.orange {
  background-color: #ffa500;
}

a.red {
  background-color: #ff4040;
}

a.turqoise {
  background-color: #30d5c8;
}

a:hover {
  background-color: #fff;
  color: #333;
  border: 1px solid #000;
}

@media (max-width: 1100px) {
  .header-container {
    grid-template-columns: 1fr;
  }

  .header-container .description {
    align-items: center;
    text-align: center;
  }

  .header-container img {
    display: none;
  }
}
</style>
