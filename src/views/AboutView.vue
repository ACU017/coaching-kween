<template>
  <div class="container">
    <div class="about">
      <h1>Welcome!</h1>
      <br />
      <h1>Here you'll learn a little bit about me!</h1>

      <p>I'm <strong>Andrea Cortes</strong>, a Full Stack Developer, Polyglot, and Writer.</p>

      <p>I hope you enjoy the projects I've uploaded here.</p>

      <h2>This is my Tech Stack</h2>
      <br />
      <div class="list">
        <ul>
          <li>MERN : MongoDb - Express - React - Node.js</li>
          <li>with MongoDB certification in progress.</li>
          <li>
            Front-end: React, with experience using libraries like Bootstrap, Tailwind, and Bulma.
          </li>
          <li>Back-end: Node.js, Express, JWT, bcrypt.</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage'
}
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.about {
  margin-top: 50px;
  text-align: center;
}

.about h1 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.about p {
  font-size: 1.2rem;
  margin-bottom: 10px;
}

.about ul {
  list-style: none;
  padding: 100;
  margin: 0;
  text-align: left;
}

.about ul li {
  font-size: 1.1rem;
  margin-bottom: 15px;
}
</style>
