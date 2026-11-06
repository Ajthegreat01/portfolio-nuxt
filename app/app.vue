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

      <div class="action-row">
        <a href="#contact" class="btn-primary">Get In Touch</a>

        <div class="social-links">
          <a href="https://github.com/Ajthegreat01" target="_blank" aria-label="GitHub">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" class="social-icon" />
          </a>
          <a href="https://www.facebook.com/aj.mayormente.2024" target="_blank" aria-label="Facebook">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/facebook/facebook-original.svg" alt="Facebook" class="social-icon" />
          </a>
          <a href="https://www.linkedin.com/in/alfred-joseph-mayormente/" target="_blank" aria-label="LinkedIn">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn" class="social-icon" />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.portfolio-container {
  min-height: 100vh;
  padding: 2rem 4rem;
  box-sizing: border-box;
  background-color: #0a0a0a;
  color: #ffffff;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 5rem;
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

.action-row {
  display: flex;
  align-items: center;
  gap: 1.5rem;
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

.social-links {
  display: flex;
  align-items: center;
  gap: 1.2rem;
}

.social-links a {
  display: flex;
  align-items: center;
  justify-content: center;
  transition: transform 0.2s ease;
}

.social-links a:hover {
  transform: translateY(-2px);
}

.social-icon {
  width: 24px;
  height: 24px;
  filter: brightness(0) invert(1);
  opacity: 0.7;
  transition: opacity 0.2s ease;
}

.social-links a:hover .social-icon {
  opacity: 1;
}
</style>