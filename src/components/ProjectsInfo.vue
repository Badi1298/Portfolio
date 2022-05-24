<template>
  <section id="section-a">
    <h1>Projects</h1>
    <div class="container-projects">
      <div class="project">
        <h3>Movies & TV Shows</h3>
        <p>
          Application which uses the TMDB API to fetch movies and TV shows,
          nicely display them in cards with title and rating, with pagination,
          allowing users to jump to a certain page, hover over them to see a
          quick overview, click on any of them to display details about them.<br /><br />
          Project built with Vue.js (HTML, CSS, JavaScript)
        </p>
      </div>
      <img src="../img/movies-tvshows.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>But-Rent-Sell</h3>
        <p>
          A complex application, allowing users to buy, rent or sell properties.
          All the properties can be clicked to display details about them. There
          is pagination between all the properties details, buy separated from
          rent.<br /><br />
          There's also a menu which allows for fast travel between pages.
          <br /><br />
          Project built with Vue.js (HTML, CSS, JavaScript)
        </p>
      </div>
      <img src="../img/buy-rent-sell.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>Coaching App</h3>
        <p>
          A complex application, allowing users to signup, login, register as
          coaches, contact other coaches that are already registered. Coaches
          that are contacted can see who contacted them in the requests tab.<br />
          <br />
          Every coach, when registering gets to select a first and last name, a
          description, an hourly rate and areas of expertise - frontend,
          backend, carrer advisory. The users can then filter coaches based on
          these areas. <br />
          <br />
          As a backend database I used Firebase (Google provided backend
          database). <br />
          <br />
          Project built with Vue.js (HTML, CSS, JavaScript)
        </p>
      </div>
      <img src="../img/coaching-app.png" alt="Project1" />
    </div>
    <div class="container-projects">
      <div class="project">
        <h3>Remember Me</h3>
        <p>
          CRUD application, allowing users to add, delete, view resources, which
          are then kept in the PostgreSQL database. Each resource consist of a
          title, description and link. <br />
          <br />
          Project built with Vue.js (HTML, CSS, JavaScript), Express.js,
          Sequalize, PostgreSQL
        </p>
      </div>
      <img src="../img/remember-me.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>Forkify</h3>
        <p>
          A complex app, which uses an API to get different recipes. There is a
          search feature, which allows to search for key words or entire
          recipes. The recipes are then displayed on the left, with pagination
          (12 per page).
          <br />
          <br />
          Once you click on a recipe, that recipe is displayed on the right,
          with all the necessary ingredients, quantity of ingredients and
          instruction on how to cook the recipe. Recipes can also be bookmarked.
          Once bookmarked they appear in the bookmarks tab.
          <br />
          <br />
          There is also an add recipe feature, which allows you to add your own
          recipes, which will then be automatically bookmarked and a small icon
          will appear next to them, to indicate the they are in fact own
          recipes.
          <br />
          <br />
          Project built with HTML, CSS and JavaScript.
        </p>
      </div>
      <img src="../img/forkify.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>Mapty</h3>
        <p>
          An application which uses the Leaflet open-source library to display a
          map of your current location, allowing you to add markers on the map
          to mark the spots where you either went for a walk or went cycling.<br /><br />
          If you choose the walk option, you can input the amount of km you
          walked, the time it took, the cadence and the program will then
          calculate the amount of miuntes it took to travel a km.<br />
          <br />
          If you choose the cycling option, you can input the amount of km you
          travelled, the time it took, the elevation gain then the program will
          calculate the speed you travelled at.
          <br />
          <br />
          Project built with HTML, CSS and JavaScript.
        </p>
      </div>
      <img src="../img/mapty.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>Pig Game</h3>
        <p>
          A game played with 2 players. Each player gets to roll the dice. While
          the player is rolling, the amount they are rolling keeps getting added
          to the current amount. At any point in time they can decide to hold,
          which adds the current amount to their total amount. If they decide to
          hold, the other player gets to roll. The catch is that if you roll a
          1, all your current points get deleted, and your total amount remains
          the same. <br />
          The first person to get to 100 total points, wins.
          <br />
          <br />
          Project built with HTML, CSS and JavaScript.
        </p>
      </div>
      <img src="../img/pig-game.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>Guess My Number</h3>
        <p>
          An application which allows you to input a number between 0 and 20,
          then the application checks if the number is the same as the randomly
          generated number, if it is lower or higher you get some feedback and
          your overall score goes down, if you guessed correctly the application
          displays the random number and your highscore is updated if necessary.
          <br />Your score starts at 20, and gets lowered by 1 each time you
          guess incorrectly. <br />
          <br />
          Project built with HTML, CSS and JavaScript.
        </p>
      </div>
      <img src="../img/guess-my-number.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>50 Projects</h3>
        <p>
          A series of 50 small to medium sized projects, aimed to strengthen
          basic knowledge of HTML, CSS and JavaScript. <br />
          <br />
          All the projects were built with HTML, CSS and JavaScript.
        </p>
      </div>
      <img src="../img/project3.jpg" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>Portfolio Website</h3>
        <p>
          A complex landing page with a home, about, work, contact tab, which
          uses CSS flexbox, CSS grid and the preprocessor scripting language
          Sass <br />
          <br />
          Project built with HTML and CSS.
        </p>
      </div>
      <img src="../img/portfolio.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>NewsGrid</h3>
        <p>
          A simple landing page with a home and about page, aimed at working
          with CSS grid. <br />
          <br />
          Project built with HTML and CSS.
        </p>
      </div>
      <img src="../img/news-grid.png" alt="Project1" />
    </div>

    <div class="container-projects">
      <div class="project">
        <h3>EdgeLedger</h3>
        <p>
          A simple landing page with a home, what, who and contact tab, aimed at
          working with CSS flexbox. <br />
          <br />
          Project built with HTML and CSS.
        </p>
      </div>
      <img src="../img/edge-ledger.png" alt="Project1" />
    </div>
  </section>
</template>

<style scoped>
section {
  max-width: 1200px;
  margin: 2rem auto;
}

section h1 {
  font-size: 2.5rem;
  padding-left: 1rem;
  margin-top: 3.5rem;
}

h3 {
  margin-bottom: 1.5rem;
  font-size: 1.4rem;
}

img {
  width: 550px;
  object-fit: cover;
  border-radius: 10px;
}

.container-projects {
  display: flex;
  padding: 0 1rem 4rem 1rem;
  margin-top: 4rem;
  margin-bottom: 9rem;
}

.project {
  padding-right: 5rem;
}

@media (max-width: 1000px) {
  .container-projects {
    flex-direction: column;
    align-items: center;
    margin-bottom: 0;
    padding: 0 1rem 0 1rem;
  }

  .container-projects h3 {
    margin-bottom: 0.5rem;
  }

  .container-projects img {
    width: 100%;
  }

  .container-projects p {
    margin-bottom: 1rem;
  }
}
</style>
