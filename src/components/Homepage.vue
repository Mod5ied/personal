<script setup>
// The following code is based off a toggle menu by @Bradcomp
// source: https://gist.github.com/Bradcomp/a9ef2ef322a8e8017443b626208999c1
// (function () {
//   var burger = document.querySelector(".burger");
//   var menu = document.querySelector("#" + burger.dataset.target);
//   burger.addEventListener("click", function () {
//     burger.classList.toggle("is-active");
//     menu.classList.toggle("is-active");
//   });
// })();
</script>

<template>
  <div>
    <!-- Navigation bar -->
    <nav class="navbar is-link is-fixed-top">
      <div class="navbar-brand">
        <div
          class="navbar-burger burger"
          data-target="navbarExampleTransparentExample"
        >
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

      <div id="navbarExampleTransparentExample" class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item" href="#about">
            <span class="icon">
              <ion-icon name="information-circle"></ion-icon>
            </span>
            <span>About</span>
          </a>
          <a class="navbar-item" href="#services">
            <span class="icon">
              <ion-icon name="construct"></ion-icon>
            </span>
            <span>Services</span>
          </a>
          <a class="navbar-item" href="#resume">
            <span class="icon">
              <ion-icon name="document-attach"></ion-icon>
            </span>
            <span>Resume</span>
          </a>
          <a class="navbar-item" href="#portfolio">
            <span class="icon">
              <ion-icon name="desktop-outline"></ion-icon>
            </span>
            <span>Portfolio</span>
          </a>
          <a class="navbar-item" href="#articles">
            <span class="icon">
              <ion-icon name="document-text"></ion-icon>
            </span>
            <span>Articles</span>
          </a>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <section class="hero is-link is-fullheight is-fullheight-with-navbar">
      <div class="hero-body">
        <div class="container">
          Hello! I am
          <h1 class="title is-1">Ogwuru Patrick</h1>
          <h2 class="subtitle is-3">Frontend Web Developer</h2>
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="section" id="about">
      <!-- Title -->
      <div class="section-heading">
        <h3 class="title is-2">About Me</h3>
        <h4 class="subtitle is-5">Jack of all trades, master of "some"</h4>
        <div class="container">
          <p>
            Web developer with more than <strong>3 years</strong> of
            well-rounded experience working with web technologies and a degree
            in the field of <strong>Computer Science</strong>, having an
            extensive knowledge of modern Web techniques and love for
            <strong>Tea</strong>. Looking for an opportunity to work and
            upgrade, as well as being involved in an organization that believes
            in gaining a competitive edge and giving back to the community.
          </p>
          <p>
            I am also an open-source contributor who loves giving back to the
            community at
            <a href="https://bulmatemplates.github.io/bulma-templates/"
              >Free Bulma Templates</a
            >
          </p>
        </div>
      </div>

      <div class="columns has-same-height">
        <div class="column">
          <!-- Profile -->
          <div class="card">
            <div class="card-content">
              <h3 class="title is-4">Profile</h3>

              <div class="content">
                <table class="table-profile">
                  <tr>
                    <th colspan="1"></th>
                    <th colspan="2"></th>
                  </tr>
                  <tr>
                    <td>Address:</td>
                    <td>Enugu State, Nigeria</td>
                  </tr>
                  <tr>
                    <td>Phone:</td>
                    <td>(+234)7013620343</td>
                  </tr>
                  <tr>
                    <td>Email:</td>
                    <td>ogwurupady@gmail.com</td>
                  </tr>
                </table>
              </div>
              <br />
              <div class="buttons has-addons is-centered" id="noWrap">
                <a href="#" class="button is-link is-small"
                  ><ion-icon name="logo-github"></ion-icon>Github</a
                >
                <a href="#" class="button is-link is-small"
                  ><ion-icon name="logo-linkedin"></ion-icon>LinkedIn</a
                >
                <a href="#" class="button is-link is-small"
                  ><ion-icon name="logo-twitter"></ion-icon>Twitter</a
                >
              </div>
            </div>
          </div>
        </div>
        <div class="column">
          <!-- Profile picture -->
          <div class="card">
            <div class="card-image">
              <figure>
                <!-- <img
                  src="https://source.unsplash.com/random/1280x960"
                  alt="Placeholder image"
                /> -->
                <img
                  src="../assets/ME.jpg"
                  alt="Placeholder image"
                  
                />
              </figure>
            </div>
          </div>
        </div>
        <div class="column">
          <!-- Skills -->
          <div class="card">
            <div class="card-content skills-content">
              <h3 class="title is-4">Skills</h3>
              <div class="content">
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <!-- <p> -->
                      <strong
                        ><ion-icon
                          class="content-icon one"
                          name="logo-javascript"
                        ></ion-icon
                        >JavaScript:</strong
                      >
                      <!-- <br /> -->
                      <p>3+ Years experience</p>
                      <!-- </p> -->
                    </div>
                  </div>
                </article>

                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <!-- <p> -->
                      <strong
                        ><ion-icon
                          class="content-icon two"
                          name="logo-vue"
                        ></ion-icon
                        >Vue.js:</strong
                      >
                      <p>3+ years experience</p>
                      <!-- </p> -->
                    </div>
                  </div>
                </article>

                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <!-- <p> -->
                      <strong
                        ><ion-icon
                          class="content-icon three"
                          name="logo-nodejs"
                        ></ion-icon
                        >Node.js:</strong
                      >
                      <p>2years(Learning)</p>
                      <!-- </p> -->
                    </div>
                  </div>
                </article>

                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <!-- <p> -->
                      <strong
                        ><ion-icon
                          class="content-icon four"
                          name="logo-html5"
                        ></ion-icon
                        >HTML5/CSS3</strong
                      >
                      <p>3+ years experience</p>
                      <!-- </p> -->
                    </div>
                  </div>
                </article>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section class="section" id="services">
      <div class="section-heading">
        <h3 class="title is-2">Services</h3>
        <h4 class="subtitle is-5">What can I do for you?</h4>
      </div>
      <div class="container">
        <div class="columns">
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Front End Web Development</h4>
                Develop Front End using latest standards with HTML5/CSS3 with
                added funtionality using JavaScript and Vue.js.
              </div>
            </div>
          </div>
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Technical Writing</h4>
                I write advanced and beginner-friendly articles focusing on
                arears of technologies that are yet to be explored or insoluble
                to devs.
              </div>
            </div>
          </div>
        </div>
        <div class="columns">
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Frontend Testing and APIs</h4>
                Build Frontend applications with cool functionalities and
                perform unit and integration test using test tools like Jest and
                Mocha. Consumption and integration of APIs.
              </div>
            </div>
          </div>
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Frontend Mentoring</h4>
                I mentor emerging and junior developers likewise, which could
                prove invaluable when working with a team of developers🙂
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Resume -->
    <section class="section" id="resume">
      <div class="section-heading">
        <h3 class="title is-2">Resume</h3>
        <h4 class="subtitle is-5">More about my past</h4>
        <!-- Add a method here that adds the spinning class to button onclick -->
        <a href="#" class="button is-warning is-medium" id="btn">
          <span class="icon">
            <ion-icon name="document-attach"></ion-icon>
          </span>
          <span>Download My Resume</span>
        </a>
      </div>
    </section>

    <!-- Portfolio -->
    <section class="section" id="portfolio">
      <div class="container">
        <div class="section-heading">
          <h3 class="title is-2">Portfolio</h3>
          <h4 class="subtitle is-5">
            A collection of my projects so far. WIP is work in progress
          </h4>
        </div>
        <br />

        <div class="container portfolio-container">
          <div class="columns is-centered">
            <div class="column is-4">
              <!-- MyNotifi -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>MyNotifi</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.1</span>
                      </a>
                      <span class="tag is-default">Vue + Firebase Auth</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="../assets/mynotifiDesk Captcha.png"
                      alt="Admin template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a
                    href="https://notify-us.vercel.app/"
                    class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/Mod5ied/MyNotifi"
                    class="card-footer-item"
                    ><ion-icon name="logo-github"></ion-icon>Source Code</a
                  >
                </footer>
              </div>
              <!-- NotesHub -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span> NotesHub </span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.2-beta</span>
                      </a>
                      <span class="tag is-default">Vue + Firebase</span>
                      <span class="tag is-danger">WIP</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image columns">
                    <img
                      src="../assets/NotesDesk Captcha.PNG"
                      alt="Cards template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="#" class="card-footer-item">Preview</a>
                  <a
                    href="https://github.com/Mod5ied/noteshub"
                    class="card-footer-item"
                    ><ion-icon name="logo-github"></ion-icon>Source Code</a
                  >
                </footer>
              </div>
              <!-- Clearon -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>ClearOn</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.2</span>
                      </a>
                      <span class="tag is-default">Vue + Firebase</span>
                      <span class="tag is-danger">WIP</span>
                      <!-- <span class="tag is-default">Mobile</span> -->
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="../assets/ClearonDesk Captcha.png"
                      alt="Hero template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a
                    href="https://clearon.netlify.app/"
                    class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/Mod5ied/Clear-On"
                    class="card-footer-item"
                    ><ion-icon name="logo-github"></ion-icon>Source Code</a
                  >
                </footer>
              </div>
              <!-- Nette -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Nette-Photo App</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <!-- <span class="tag is-default">v0.1.2</span> -->
                      </a>
                      <span class="tag is-default">Vue+Typescript</span>
                      <span class="tag is-danger">WIP</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="../assets/Nette Captcha.PNG"
                      alt="Landing template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/landing.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/Mod5ied/Nette/"
                    class="card-footer-item"
                    ><ion-icon name="logo-github"></ion-icon>Source Code</a
                  >
                </footer>
              </div>
              <!-- Autosearch -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Autocomplete component</span>
                    <span class="is-pulled-right">
                      <a href="#">
                        <span class="tag is-default">v0.1</span>
                      </a>
                      <span class="tag is-default">Vue3 + Typescript</span>
                      <!-- <span class="tag is-danger">WIP</span> -->
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="../assets/NotesDesk Captcha.PNG"
                      alt="Landing template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/instaAlbum.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/instaAlbum.html"
                    class="card-footer-item"
                    ><ion-icon name="logo-github"></ion-icon>Source Code</a
                  >
                </footer>
              </div>
              <!-- Forms -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Forms component</span>
                    <span class="is-pulled-right">
                      <a href="#">
                        <span class="tag is-default">v0.1</span>
                      </a>
                      <span class="tag is-default">Vue3</span>
                      <span class="tag is-danger">WIP</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="../assets/Form CPTCHA.PNG"
                      alt="Landing template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/instaAlbum.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/instaAlbum.html"
                    class="card-footer-item"
                    ><ion-icon name="logo-github"></ion-icon>Source Code</a
                  >
                </footer>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Articles -->
    <div class="section is-centered" id="articles">
      <div class="section-heading">
        <h3 class="title is-2">Articles</h3>
        <h4 class="subtitle is-5">Curated beginner to advanced articles.</h4>
      </div>
      <br />
      <div class="columns">
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">
                <a href="">A Beginners Introduction to the Web</a>
              </h4>
              Develop Front End using latest standards with HTML5/CSS3 with
              added funtionality using JavaScript and Vue.js.
            </div>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">
                <a href=""> Beginners Introduction to Request and Response </a>
              </h4>
              I write advanced and beginner-friendly articles focusing on arears
              of technologies that are yet to be explored or insoluble to devs.
            </div>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">
                <a href="">
                  Vue3 concepts You Don't Know!
                  <span class="tag is-danger">WIP</span>
                </a>
              </h4>
              I write advanced and beginner-friendly articles focusing on arears
              of technologies that are yet to be explored or insoluble to devs.
            </div>
          </div>
        </div>
      </div>
      <!-- second wave -->
      <div class="columns">
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">
                <a href="">
                  Article Four <span class="tag is-danger">WIP</span></a
                >
              </h4>
              I write advanced and beginner-friendly articles focusing on arears
              of technologies that are yet to be explored or insoluble to devs.
            </div>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">
                <a href="">
                  Article Five <span class="tag is-danger">WIP</span></a
                >
              </h4>
              I write advanced and beginner-friendly articles focusing on arears
              of technologies that are yet to be explored or insoluble to devs.
            </div>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <div class="content">
              <h4 class="title is-5">
                <a class="is-warning" href="">
                  Article Six <span class="tag is-danger">WIP</span></a
                >
              </h4>
              I write advanced and beginner-friendly articles focusing on arears
              of technologies that are yet to be explored or insoluble to devs.
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Footer -->
    <footer class="footer pb-3rem">
      <div class="section-heading">
        <p>
          <strong>Bulma Personal Template</strong> by
          <a href="https://bulmatemplates.github.io/bulma-templates/"
            >Free Bulma Templates 💝</a
          >
        </p>
        <p>
          I am a <a href="www.github.com/mod5ied/">contributor</a> on Bulma Free
          Templates 😊
        </p>
      </div>
    </footer>
  </div>
</template>

<style>
* {
  /* outline: 1px solid red !important; */
  font-family: "Rubik", sans-serif;
}
.has-same-height .card {
  height: 320px;
  overflow: hidden;
}
.card-content h3 {
  text-align: center;
}
.table-profile td,
th {
  border: none !important;
  border-bottom: 1px solid rgba(0, 0, 0, 0.075) !important;
}
.table-profile td:first-of-type {
  font-weight: bold;
}
.table-profile .buttons {
  display: flex;
  flex-direction: row;
  align-items: center;
  flex-wrap: nowrap !important;
}
#noWrap {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: nowrap;
}
.skills-content .media {
  margin: 0 !important;
  padding: 4px !important;
  border: 0 !important;
  border-bottom: 1px solid rgba(0, 0, 0, 0.075) !important;
}
.skills-content .content strong {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  gap: 0.3rem;
  text-align: left !important;
}
.skills-content .content .one,
.skills-content .content .four {
  color: rgb(195, 205, 50);
  background: black;
}
.skills-content .content .two,
.skills-content .content .three {
  color: limegreen;
}
.custom-tags {
  text-align: center !important;
  display: block;
}
.portfolio-container .card {
  margin-bottom: 2em;
}
.section-heading {
  text-align: center;
  margin-top: 1em;
  margin-bottom: 6em;
}
.section-heading #btn:hover {
  background: transparent !important;
  border: 2px solid #ffdd57;
  color: #f1c824;
}
.columns .box #btn {
  height: 50px;
}
</style>
