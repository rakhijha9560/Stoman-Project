<template>
  <div>
    <!-- start nav -->

    <nav>
      <img
        id="Dark-logo"
        src="https://vuejs-tailwindcss-portfolio.netlify.app/img/logo-dark.f5ad932e.svg"
        alt="Dark-logo" />
      <div class="nav-list">
        <a>Projects</a>
        <a>About Me</a>
        <a>Contact</a>
      </div>
      <div class="nav-button-box">
        <button id="btn-1">Hire Me</button>
        <i class="ri-moon-line"></i>
      </div>
    </nav>
    <!-- End nav -->
    <!-- start developer section -->
    <div>
      <section>
        <div class="dev-section">
          <div class="dev-text">
            <h1 id="h1-text">HI, IAM STOMAN</h1>
            <p id="p1-text">A Full-Stack Developer & Design</p>
            <p id="p2-text">Enthusiast</p>
            <div class="download-btn-container">
              <a
                id="pdf-link"
                href="https://vuejs-tailwindcss-portfolio.netlify.app/files/Stoman-Resume.pdf"
                ><button id="download-btn">
                 
                  <span> <i class="ri-arrow-down-circle-line"></i>Download CV</span></button></a
              >
            </div>
          </div>
          <div class="Developer-img">
            <img
              src="https://vuejs-tailwindcss-portfolio.netlify.app/img/developer.d30886eb.svg"
              alt="Developer" />
          </div>
        </div>
      </section>
    </div>

    <!-- End developer section -->
    <!-- start Portfolio section -->
    <section>
      <div class="container">
        <div>
          <p id="project-heading">Projects Portfolio</p>
        </div>
        <div>
          <h3>Search projects by title or filter by category</h3>
        </div>
        <div class="search-input-container">
          <div>
            <i class="ri-search-line"></i>
            <input
              type="search"
              id="name"
              name="name"
              placeholder="Search Projects" />
          </div>
          <div>
            <select>
              <option>All Projects</option>
              <option value="Web Application">Web Application</option>
              <option value="Mobile Application">Mobile Application</option>
              <option value="UI/UX Design">UI/UX Design</option>
              <option value="Branding & Anim">Branding & Anim</option>
            </select>
          </div>
        </div>
        <div class="projects-container">
          <div class="card">
            <a>
              <div class="image">
                <img
                  src="https://vuejs-tailwindcss-portfolio.netlify.app/img/web-project-2.ecd6c182.jpg"
                  alt="Google Health Platform" />
              </div>
              <div class="info">
                <p>Google Health Platform</p>
                <span>Web Application</span>
              </div>
            </a>
          </div>
          <div class="card">
            <a>
              <div class="image">
                <img
                  src="https://vuejs-tailwindcss-portfolio.netlify.app/img/mobile-project-2.9bd76372.jpg"
                  alt="Phoenix Digital Agency" />
              </div>
              <div class="info">
                <p>Phoenix Digital Agency</p>
                <span>Mobile Application</span>
              </div>
            </a>
          </div>
          <div class="card">
            <a>
              <div class="image">
                <img
                  src="https://vuejs-tailwindcss-portfolio.netlify.app/img/ui-project-1.96e7f21e.jpg"
                  alt="Project Management UI" />
              </div>
              <div class="info">
                <p>Project Management UI</p>
                <span>UI/UX Design</span>
              </div>
            </a>
          </div>
         
          <div class="card">
            <a>
              <div class="image">
                <img
                  src="https://vuejs-tailwindcss-portfolio.netlify.app/img/ui-project-2.afd87ce7.jpg"
                  alt="Cloud Storage Platform" />
              </div>
              <div class="info">
                <p>Cloud Storage Platform</p>
                <span>UI/UX Design</span>
              </div>
            </a>
          </div>
          <div class="card">
            <a>
              <div class="image">
                <img
                  src="https://vuejs-tailwindcss-portfolio.netlify.app/img/mobile-project-1.8b4f9e2f.jpg"
                  alt="React Social App" />
              </div>
              <div class="info">
                <p>React Social App</p>
                <span>Mobile Application</span>
              </div>
            </a>
          </div>
          <div class="card">
            <a>
              <div class="image">
                <img
                  src="https://vuejs-tailwindcss-portfolio.netlify.app/img/web-project-1.d1debdf5.jpg"
                  alt="Apple Design System" />
              </div>
              <div class="info">
                <p>Apple Design System</p>
                <span>Mobile Application</span>
              </div>
            </a>
          </div>
       
        </div>
      </div>
      <div class="project-button">
        <a>
          <button>More Projects</button>
        </a>
      </div>
    </section>
    <!-- End Portfolio section -->
  </div>
  <!-- START CONTACT SECTION -->
  <div>
    <div class="contact-box">
      <p>Follow me</p>
      <ul>
        <a href="https://www.stoman.me/"><i class="ri-user-fill"></i></a>
        <a href="https://github.com/realstoman"><i class="ri-github-line"></i></a>
        <a href="https://twitter.com/realstoman"><i class="ri-twitter-line"></i></a>
        <a href="https://www.linkedin.com/in/realstoman/"><i class="ri-linkedin-fill"></i></a>
        <a href="https://www.youtube.com/c/realstoman"><i class="ri-youtube-line"></i></a>
      </ul>
    </div>
    <div class="Credit-box">
      <div class="text">
        © 2023.
        <a href="https://github.com/realstoman/vuejs-tailwindcss-portfolio"
          >Vue.js & Tailwind CSS Portfolio</a
        >
        . Developed by <a href="https://www.stoman.me/">STOMAN</a>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
