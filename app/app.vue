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
  letter-spacing: 1px;
}

.nav-links a {
  color: #a3a3a3;
  text-decoration: none;
  margin-left: 2rem;
  font-size: 0.95rem;
  font-weight: 500;
  transition: color 0.2s ease;
}

.nav-links a:hover {
  color: #ffffff;
}

.hero-content {
  max-width: 600px;
}

.greeting {
  font-size: 1.1rem;
  color: #a3a3a3;
  margin-bottom: 0.5rem;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.name {
  font-size: 3.2rem;
  font-weight: 800;
  line-height: 1.1;
  margin-bottom: 1.2rem;
  color: #ffffff;
}

.name span {
  color: #737373;
}

.description {
  font-size: 1.05rem;
  color: #d4d4d4;
  margin-bottom: 2rem;
  line-height: 1.6;
}

.btn-primary {
  display: inline-block;
  background-color: #ffffff;
  color: #000000;
  padding: 0.8rem 1.8rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
  transition: all 0.2s ease;
  border: 1px solid #ffffff;
}

.btn-primary:hover {
  background-color: #000000;
  color: #ffffff;
}
</style>