<template>
  <section>
    <h1>Resume</h1>
    <div class="container">
      <h2>Work Experience</h2>
      <div class="experience">
        <div class="time-span">
          <p>Jul 2022-Now</p>
        </div>
        <div class="info">
          <h3>Flowmatters</h3>
          <p>
            In the time spent at Flowmatters, I've done the following:
            <br />
            • Implemented user interfaces for web applications.
            <br />
            • Collaborated closely with cross-functional teams, including
            designers and back-end developers.
            <br />
            • Ensured the usability, accessibility, and performance of web
            applications across various browsers and devices.
            <br />
            • Participated in the migration of a website from version 2.0 to
            3.0, working with new and improved technologies, gaining a lot of
            experience in the process.
            <br />
            • Demonstrated adaptability and problem-solving skills throughout
            the migration process.
          </p>
        </div>
        <div class="time-span">
          <p>Jan 2022-Jul 2022</p>
        </div>
        <div class="info">
          <h3>None</h3>
          <p>
            I have been taking courses and learning as much as I can since the
            beginning of the year, until now, and will continue to take courses,
            learn and improve.
          </p>
        </div>
      </div>
    </div>
    <div class="line"></div>
    <div class="container">
      <h2>Education</h2>
      <div class="experience">
        <div class="time-span">
          <p>2017-2021</p>
        </div>
        <div class="info">
          <h3>University Of Medicine and Pharmacy</h3>
          <p>
            The 2 university choices that I had in mind were: The Technical
            University of Cluj-Napoca, Romania and The University of Medicine
            and Pharmacy, Targu Mures, Romania. I chose the latter, and after 4
            years of studying medicine, it was clear as day that it was
            defintely not meant for me, so I decided to take a leap of faith,
            and do the thing I should have done in the first place, which is
            computer programming.
          </p>
        </div>
        <div class="time-span">
          <p>2013-2017</p>
        </div>
        <div class="info">
          <h3>Highschool</h3>
          <p>
            I went to the "Mircea Eliade" Highschool, in Sighișoara, Romania.
            Graduated with the highest average grade out of every student in
            every class - 9.80.
          </p>
        </div>
      </div>
    </div>
    <div class="line"></div>
    <div class="container-expertise">
      <h2>Skill & Expertise</h2>
      <div class="expertise">
        <ul>
          <li>
            <p>
              HTML, CSS, Tailwind CSS, JavaScript, Typescript
              <br />
              <br />
              Vue.js, Nuxt.js, React.js, Next.js
              <br />
              <br />
              Node.js, Express.js, GraphQL, MongoDB, PostgreSQL, Websockets
              <br />
              <br />
              Weflow, Git, Bitbucket, Jira
            </p>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<style scoped>
section {
  max-width: 1100px;
  margin: 2rem auto;
}

section h1 {
  font-size: 2.5rem;
  padding-left: 1rem;
  margin-top: 3.5rem;
}

.container {
  display: grid;
  grid-template-columns: 1fr 1.5fr;
  padding: 0 1rem 4rem 1rem;
  margin-top: 4rem;
}

.experience {
  display: grid;
  grid-template-columns: 1fr 3fr;
  grid-gap: 3rem;
}

.info p {
  margin-top: 0.2rem;
}

.container-expertise {
  display: grid;
  grid-template-columns: 3fr 2fr;
  padding: 0 1rem 4rem 1rem;
  margin-top: 4rem;
}

.expertise ul {
  list-style-type: none;
}

.expertise ul li p {
  padding: 1rem 0;
}

.line {
  background: #777;
  padding: 1px;
}

@media (max-width: 850px) {
  .container {
    grid-template-columns: 1fr;
    margin: 0;
  }

  .container h2 {
    margin-bottom: 0.5rem;
    margin-top: 2rem;
  }

  .container .experience {
    grid-template-columns: 1fr;
    grid-gap: 0rem;
  }

  .container .experience .time-span {
    margin-top: 2rem;
  }

  .container-expertise {
    grid-template-columns: 1fr;
    margin-top: 2rem;
    padding: 0 1rem;
  }
}
</style>
