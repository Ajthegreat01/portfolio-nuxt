<template>
  <div class="container">
    <h1>Alfred Joseph Mayormente</h1>
    <p>Nuxt 4 Portfolio Initial Setup</p>
  </div>
</template>

<style scoped>
.container {
  font-family: sans-serif;
  padding: 2rem;
  color: #fff;
  background-color: #0f172a;
  min-height: 100vh;
}
</style>

<template>
  <div class="container">
    <header>
      <h1>Alfred Joseph Mayormente</h1>
      <p class="subtitle">Nuxt 4 & Frontend Developer</p>
    </header>

    <section class="projects">
      <h2>Featured Project</h2>
      <div class="card">
        <h3>Nuxt 4 Portfolio Web Application</h3>
        <p>A fast, SSR-enabled portfolio built with Nuxt 4 and deployed on Render platform.</p>
        <div class="tags">
          <span>Nuxt 4</span>
          <span>Vue 3</span>
          <span>Render</span>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.container {
  font-family: sans-serif;
  padding: 3rem 10%;
  color: #f8fafc;
  background-color: #0f172a;
  min-height: 100vh;
}
.subtitle { color: #00dc82; font-weight: 600; }
.projects { margin-top: 2rem; }
.card {
  background: #1e293b;
  padding: 1.5rem;
  border-radius: 8px;
  border: 1px solid #334155;
}
.tags span {
  background: #0f172a;
  color: #00dc82;
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  font-size: 0.8rem;
  margin-right: 0.5rem;
}
</style>
