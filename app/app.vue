<template>
  <div class="portfolio-container">
    <!-- Navbar -->
    <header class="navbar">
      <div class="logo">AJ</div>
      <nav class="nav-links">
        <a href="#about">About</a>
        <a href="#tech-stack">Tech Stack</a>
        <a href="#certifications">Certifications</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

<template>
  <!-- Main Hero Content Only -->
  <div class="hero-content">
    <p class="greeting">Hello, I'm</p>
    <h1 class="name">Alfred Joseph <span>Mayormente</span></h1>
    <p class="description">
      Aspiring Web Developer passionate about creating responsive and modern websites.
    </p>

    <a href="#contact" class="btn-primary">Get In Touch</a>
  </div>
</template>

<style scoped>
.hero-content {
  max-width: 500px;
}

.greeting {
  font-size: 1.1rem;
  color: #1e3a8a;
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
  color: #1e293b;
}

.description {
  font-size: 1rem;
  color: #e2e8f0;
  margin-bottom: 1.5rem;
  line-height: 1.5;
}

.btn-primary {
  display: inline-block;
  background-color: #000080;
  color: #ffffff;
  padding: 0.7rem 1.6rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  transition: background-color 0.2s ease;
}

.btn-primary:hover {
  background-color: #000066;
}
</style>