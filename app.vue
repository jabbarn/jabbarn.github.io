<template>
  <section>
    <header>
      <h1>Noman Jabbar | Software Developer</h1>
      <div class="buttons">
        <!-- heroicons-solid:sun  heroicons-solid:moon -->
        <a href="mailto:nomanjabbar1999@gmail.com?SUBJECT=Hi there 👋"><Icon name="octicon:mail-24" size="2em"/></a>
        <a target="_blank" href="https://www.linkedin.com/in/njabbar/"><Icon name="bxl:linkedin" size="2em"/></a>
        <a target="_blank" href="https://github.com/jabbarn"><Icon name="uil:github" size="2em"/></a>
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