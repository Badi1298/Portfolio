<template>
  <nav>
    <div>
      <h2><router-link to="/aboutme">Șerban David</router-link></h2>
      <p><i class="fa-solid fa-desktop"></i> Programmer</p>
    </div>
    <ul>
      <li>
        <router-link
          to="/aboutme"
          :class="{ active: currentRoute === '/aboutme' }"
          >About Me</router-link
        >
      </li>
      <li>
        <router-link
          to="/resume"
          :class="{ active: currentRoute === '/resume' }"
          >Resume</router-link
        >
      </li>
      <li>
        <router-link
          to="/projects"
          :class="{ active: currentRoute === '/projects' }"
          >Projects</router-link
        >
      </li>
      <li>
        <router-link
          to="/contact"
          :class="{ active: currentRoute === '/contact' }"
          >Contact</router-link
        >
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  computed: {
    currentRoute() {
      return this.$route.path;
    },
  },
};
</script>

<style scoped>
nav {
  max-width: 1900px;
  margin: 1.5rem auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

div {
  display: flex;
  align-items: center;
}

h2 {
  margin-left: 2rem;
  margin-right: 1rem;
}

a {
  color: #333;
}

ul {
  display: flex;
  flex-direction: row;
  margin-right: 2rem;
  margin-top: 0.4rem;
}

p {
  margin-top: 0.4rem;
}

ul li:nth-child(1),
ul li:nth-child(2),
ul li:nth-child(3) {
  border-right: 1px solid #333;
}

ul li a {
  padding: 1rem;
}

ul li a:hover {
  color: #777;
}

.active {
  color: #deaa88;
}
</style>
