<template>
  <div class="portfolio-container">
    <header class="navbar">
      <div class="logo">AJ</div>
      <nav class="nav-links">
        <a href="#about">About</a>
        <a href="#tech-stack">Tech Stack</a>
        <a href="#certifications">Certifications</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <div class="hero-content">
      <p class="greeting">Hello, I'm</p>
      <h1 class="name">Alfred Joseph <span>Mayormente</span></h1>
      <p class="description">
        Aspiring Web Developer passionate about creating responsive and modern web applications.
      </p>

      <a href="#contact" class="btn-primary">Get In Touch</a>
    </div>
  </div>
</template>

<style scoped>
.portfolio-container {
  min-height: 100vh;
  padding: 2rem;
  box-sizing: border-box;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 3rem;
}

.logo {
  font-weight: 800;
  font-size: 1.5rem;
  color: #ffffff;
}

.nav-links a {
  color: #e2e8f0;
  text-decoration: none;
  margin-left: 1.5rem;
  font-size: 0.95rem;
  transition: color 0.2s ease;
}

.nav-links a:hover {
  color: #38bdf8;
}

.hero-content {
  max-width: 500px;
}

.greeting {
  font-size: 1.1rem;
  color: #38bdf8;
  margin-bottom: 0.4rem;
  font-weight: 600;
}

.name {
  font-size: 2.8rem;
  font-weight: 800;
  line-height: 1.1;
  margin-bottom: 1rem;
  color: #ffffff;
}

.name span {
  color: #94a3b8;
}

.description {
  font-size: 1rem;
  color: #e2e8f0;
  margin-bottom: 1.5rem;
  line-height: 1.5;
}

.btn-primary {
  display: inline-block;
  background-color: #2563eb;
  color: #ffffff;
  padding: 0.7rem 1.6rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  transition: background-color 0.2s ease;
}

.btn-primary:hover {
  background-color: #1d4ed8;
}
</style>