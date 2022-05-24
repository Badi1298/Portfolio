<template>
  <footer>
    <div class="footer-container">
      <div class="phone">
        <h3>Phone</h3>
        <p>0744-750-373</p>
      </div>
      <div>
        <h3>Email</h3>
        <p>serbandavid83@yahoo.com</p>
      </div>
      <div class="follow">
        <h3>Follow me</h3>
        <a href="https://www.facebook.com/serban.david.5" target="_blank"
          ><i class="fa-brands fa-facebook fa-2x"></i
        ></a>
        <a href="https://www.instagram.com/badi9812/" target="_blank"
          ><i class="fa-brands fa-instagram fa-2x"></i
        ></a>
      </div>
      <p class="copyright">
        Copyright &copy; 2022, By Șerban David <br />
        All Rights Reserved
      </p>
    </div>
  </footer>
</template>

<style scoped>
.footer-container {
  width: 100%;
  display: grid;
  grid-template-columns: 2fr 3fr 2fr 1fr;
  padding: 3rem;
  border-top: 1px solid #777;
}

.follow a {
  padding: 0 0.3rem;
  color: #333;
}

@media (max-width: 750px) {
  .footer-container {
    grid-template-columns: repeat(2, 1fr);
    margin-top: 5rem;
  }

  .footer-container .phone {
    margin-bottom: 1rem;
  }
}

@media (max-width: 550px) {
  .footer-container {
    grid-template-columns: repeat(1, 1fr);
  }

  .footer-container .follow {
    margin-top: 1rem;
  }

  .footer-container .copyright {
    margin-top: 1rem;
  }
}
</style>
