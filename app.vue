<template>
  <section>
    <header>
      <h1>Noman Jabbar | Software Developer</h1>
      <div class="buttons">
        <!-- heroicons-solid:sun  heroicons-solid:moon -->
        <a href="mailto:nomanjabbar1999@gmail.com?SUBJECT=Hi there 👋">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="icon" style="" width="2em" height="2em" viewBox="0 0 24 24" data-v-9c34c54e="">
            <path fill="currentColor" d="M1.75 3h20.5c.966 0 1.75.784 1.75 1.75v14a1.75 1.75 0 0 1-1.75 1.75H1.75A1.75 1.75 0 0 1 0 18.75v-14C0 3.784.784 3 1.75 3ZM1.5 7.412V18.75c0 .138.112.25.25.25h20.5a.25.25 0 0 0 .25-.25V7.412l-9.52 6.433c-.592.4-1.368.4-1.96 0Zm0-2.662v.852l10.36 7a.25.25 0 0 0 .28 0l10.36-7V4.75a.25.25 0 0 0-.25-.25H1.75a.25.25 0 0 0-.25.25Z"></path>
          </svg>
        </a>
        <a target="_blank" href="https://www.linkedin.com/in/njabbar/">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="icon" style="" width="2em" height="2em" viewBox="0 0 24 24" data-v-9c34c54e="">
            <circle cx="4.983" cy="5.009" r="2.188" fill="currentColor"></circle>
            <path fill="currentColor" d="M9.237 8.855v12.139h3.769v-6.003c0-1.584.298-3.118 2.262-3.118c1.937 0 1.961 1.811 1.961 3.218v5.904H21v-6.657c0-3.27-.704-5.783-4.526-5.783c-1.835 0-3.065 1.007-3.568 1.96h-.051v-1.66H9.237zm-6.142 0H6.87v12.139H3.095z"></path>
          </svg>
        </a>
        <a target="_blank" href="https://github.com/jabbarn">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="icon" style="" width="2em" height="2em" viewBox="0 0 24 24" data-v-9c34c54e="">
            <path fill="currentColor" d="M12 2.247a10 10 0 0 0-3.162 19.487c.5.088.687-.212.687-.475c0-.237-.012-1.025-.012-1.862c-2.513.462-3.163-.613-3.363-1.175a3.636 3.636 0 0 0-1.025-1.413c-.35-.187-.85-.65-.013-.662a2.001 2.001 0 0 1 1.538 1.025a2.137 2.137 0 0 0 2.912.825a2.104 2.104 0 0 1 .638-1.338c-2.225-.25-4.55-1.112-4.55-4.937a3.892 3.892 0 0 1 1.025-2.688a3.594 3.594 0 0 1 .1-2.65s.837-.262 2.75 1.025a9.427 9.427 0 0 1 5 0c1.912-1.3 2.75-1.025 2.75-1.025a3.593 3.593 0 0 1 .1 2.65a3.869 3.869 0 0 1 1.025 2.688c0 3.837-2.338 4.687-4.563 4.937a2.368 2.368 0 0 1 .675 1.85c0 1.338-.012 2.413-.012 2.75c0 .263.187.575.687.475A10.005 10.005 0 0 0 12 2.247Z"></path>
          </svg>
        </a>
      </div>
    </header>
  
    <hr style="border-width: 2px;"/>
  
    <div class="profile qual full-qual" id="pro">
      <h2 class="box">My Profile</h2>
      <img class="avatar" src="./public/me.jpg" alt="picture of the author.">
      <p>
        Greetings! My name is Noman Jabbar, a dedicated {{ getAge("1999/06/17") }} year old born in Amsterdam with a deep-rooted passion for Software Engineering.
      </p>
      <p>
        With 7 years of studying and 2 years of experience, I am still learning as well as improving my skills in problem solving and actively communicating. My commitment to excellence and a results-driven approach have consistently led to successful projects and positive feedback from my coworkers. Adept at frontend development, I am eager to contribute my expertise to a dynamic team and make a meaningful impact.
      </p>
      <p>
        Outside of work, I actively engage in going on short walks, taking care of my parakeets and watching shows which fuel my creativity.
      </p>
      <p>
        I am ready to leverage my experience and enthusiasm to excel in my next role, contributing effectively to organizational goals aswell as my own personal goals. One personal goal being to gain more experience in languages such as Rust, C++ and Clojure.
      </p>
      <br>
      <div class="additional-info">
        <p>To find more about me:</p>
        <p>Check out my <strong>Linkedin</strong>: <a href="https://www.linkedin.com/in/njabbar/">https://www.linkedin.com/in/njabbar/</a></p>
        <p>Check out my <strong>Github</strong>: <a href="https://github.com/jabbarn">https://github.com/jabbarn</a></p>
        <p>Or just shoot me up with an <strong>email</strong> on nomanjabbar1999@gmail.com</p>
      <br>
      </div>
    </div>

    <div class="xp qual full-qual">
      <h2 class="box" id="xp">Experience</h2>
      
      <div class="data">
        <div class="data-item" id="item1">
          <h5>Store Employee<br><span>Zeeman</span></h5>
          <span class="symbol">&nbsp;</span>
        </div>
        
        <div class="data-item" id="item2">
          <h5>Store Employee<br><span>Marqt</span></h5>
          <span class="symbol">&nbsp;</span>
        </div>
        
        <div class="data-item" id="item3">
          <h5>Intern Frontend Developer<br><span>ItsaVirus</span></h5>
          <span class="symbol">&nbsp;</span>
        </div>
        
        <div class="data-item" id="item4">
          <h5>Intern Fullstack Developer<br><span>Aldewereld Consultancy</span></h5>
          <span class="symbol">&nbsp;</span>
        </div>
        
        <div class="data-item" id="item5">
          <h5>Intern Blockchain Developer <br><span>Effect Network</span></h5>
          <span class="symbol">&nbsp;</span>
        </div>
        
        <div class="data-item" id="item6">
          <h5>Intern BI Specialist<br><span>Zeeman</span></h5>
          <span class="symbol">&nbsp;</span>
        </div>
        
        <div class="highlighted data-item" id="item7">
          <h5> Store Employee<br><span>Zeeman</span></h5>
          <span class="symbol">&nbsp;</span>
        </div>
      </div>
      
      <hr/>
      <div class="years">
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2015</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2016</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2017</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2018</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2019</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2020</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2021</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2022</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2023</div>
        </div>
        <div class="year-item">
          <div class="dot">&#183;</div>
          <div class="year">2024</div>
        </div>
      </div>
      <span></span>
    </div>
    
    <div class="edu qual third-qual">
      <h2 class="box" id="edu">Education</h2>
      <span class="uni">
        Amsterdam University of Applied Sciences - Graduated 2023
      </span>

      <div class="wrap">    
        
        
        <div class="schools">
          <div class="up-arrow school-item" id="school1">
            <h5>Sweelinck College<br><span>VMBO-T</span></h5>
            <span class="symbol">&nbsp;</span>
          </div>
          <div class="up-arrow school-item" id="school2">
            <h5>ROCvA Zuidoost<br><span>MBO-ICT</span></h5>
            <span class="symbol">&nbsp;</span>
          </div>
          
          <div class="up-arrow school-item" id="school3">
            <h5>AUAS<br><span>HBO-ICT SE</span></h5>
            <span class="symbol">&nbsp;</span>
          </div>
        </div>
        
        <hr/>
        <div class="years">
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2012</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2013</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2014</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2015</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2016</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2017</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2018</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2019</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2020</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2021</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2022</div>
          </div>
          <div class="year-item">
            <div class="dot">&#183;</div>
            <div class="year">2023</div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="hni qual quarter-qual">
      <h3 class="box">Hobbies &amp; Interests</h3>
        <ul>
          <li> Spare time programming
            <ul>
              <li>Fabric Minecraft Mods</li>
              <li>Discord Bots</li>
            </ul>
          </li>
          <br/>
          <li>Reading (documentation)</li>
          <li>Watching shows</li>
          <li>Going on short walks</li>
        </ul>
    </div>
      
    <div class="sknex">
      <h2 class="box" id="s&e">Skills &amp; Expertise</h2>
      <br/>
      <div class="skills-container">
      <div class="skills">
        <h3 class="line">Languages</h3>
          <hr/>
        <section class="skill">
          <p class="skill-text">Dutch</p>
          <div class="blobs">
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">English</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Urdu</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
      </div>
      <div class="skills">
          <h3 class="line">Software Languages</h3>
          <hr/>
          <section class="skill">
          <p class="skill-text">HTML / XML</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">JSON</p>
          <div class="blobs">
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">(S)CSS / LESS</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Javascript</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Typescript</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Java</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">PHP</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Python</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Clojure</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">C++</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Rust</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">SQL</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">MongoDB</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
      </div>
      <div class="skills">
        <h3 class="line">Frameworks</h3>
          <hr/>
        <section class="skill">
          <p class="skill-text">Laravel</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Spring</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Flask</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">React / Next</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Vue / Nuxt</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Drupal</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Angular</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Selenium</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Jasmine</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Jest</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Karma</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">JUnit</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
      </div>
      <div class="skills">
        <h3 class="line">Miscellaneous</h3>
          <hr/>
        <section class="skill">
          <p class="skill-text">GIT</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Scrum</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Powershell</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">bash / zsh</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">Docker</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
        <section class="skill">
          <p class="skill-text">DBeaver</p>
          <div class="blobs">
            <span class="blob"></span>
            <span class="blob"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
            <span class="blob filled"></span>
          </div>
        </section>
      </div>
    </div>
    </div>
    <footer class="footer">
    <div class="waves">
      <div class="wave" id="wave1"></div>
      <div class="wave" id="wave2"></div>
      <div class="wave" id="wave3"></div>
      <div class="wave" id="wave4"></div>
    </div>
    <ul class="social-icon">
      <li class="social-icon__item"><a class="social-icon__link" href="#">
          <ion-icon name="logo-facebook"></ion-icon>
        </a></li>
      <li class="social-icon__item"><a class="social-icon__link" href="#">
          <ion-icon name="logo-twitter"></ion-icon>
        </a></li>
      <li class="social-icon__item"><a class="social-icon__link" href="#">
          <ion-icon name="logo-linkedin"></ion-icon>
        </a></li>
      <li class="social-icon__item"><a class="social-icon__link" href="#">
          <ion-icon name="logo-instagram"></ion-icon>
        </a></li>
    </ul>
    <p>&copy; {{ new Date().getFullYear() }} Noman Jabbar </p>
  </footer>
  </section>
</template>

<script setup>
    const getAge = (dateString) => {
      var today = new Date();
      var birthDate = new Date(dateString);
      var age = today.getFullYear() - birthDate.getFullYear();
      var m = today.getMonth() - birthDate.getMonth();
      if (m < 0 || (m === 0 && today.getDate() < birthDate.getDate())) {
          age--;
      }
      return age;
    }
</script>

<style>
  @import '~/assets/scss/main.scss';
</style>