<!-- eslint-disable vuejs-accessibility/anchor-has-content -->
<!-- eslint-disable max-len -->
<template>
  <div class="home">
    <div class="container">
      <section class="first">
        <div class="slogan">
          Разработка веб- и мобильных приложений.
        </div>
        <div>
          <div class="greetings">
            Привет, меня зовут Владимир Петров
          </div>
          <h1>
            Website & Mobile App Developer
          </h1>
          <!-- <h1>
            Frontend Web <br> & Mobile App Developer
          </h1> -->
        </div>
      </section>
      <section class="second">
        <div class="title">
          кто я?
        </div>
        <div class="about-me">
          <p>Более 2 лет я занимаюсь разработкой сайтов и мобильных приложений. Я с большой ответственностью и серьезностью подхожу к работе, поэтому создаю высококачественные сервисы. Вы можете нанять меня на работу, предложить сотрудничество или заказать разработку сайта.</p>
          <div class="skills">
            <span>Высокий уровень знаний</span>
            <div>
              <div class="skill">HTML</div>
              <div class="skill">CSS</div>
              <div class="skill">JS</div>
              <div class="skill">VUE</div>
              <div class="skill">React</div>
              <div class="skill">Flutter</div>
            </div>
            <span>Поменьше</span>
            <div>
              <div class="skill">Node.js (Express)</div>
              <div class="skill">Django</div>
              <div class="skill">Git</div>
              <div class="skill">Docker</div>
              <div class="skill">Figma</div>
              <div class="skill">C#</div>
            </div>
            <span>Образование</span>
            <div>
              <div class="skill">Прикладная Информатика (высшее)</div>
            </div>
            <span>Город проживания</span>
            <div>
              <div class="skill">Екатеринбург</div>
            </div>
            <span>Возраст</span>
            <div>
              <div class="skill">23</div>
            </div>
          </div>
        </div>
      </section>
      <section class="experience">
        <div class="title">Опыт работы</div>
        <div class="exp-items">
          <div class="exp-item">
            <div class="vline"></div>
            <div class="info">
              <span class="year"> 2024 - ?</span>
              <span class="org">Здесь может быть ваша компания</span>
              <span class="post">Middle Frontend Developer</span>
            </div>
          </div>
          <div class="exp-item">
            <div class="vline"></div>
            <div class="info">
              <span class="year"> фев. 2022 — сент. 2023</span>
              <span class="org">ФГАОУ ВО «УрФУ имени первого Президента России Б.Н. Ельцина»</span>
              <span class="post">Junior Frontend Developer</span>
            </div>
          </div>
          <div class="exp-item">
            <div class="vline"></div>
            <div class="info">
              <span class="year"> 2021 — 2022</span>
              <span class="org">Фриланс</span>
              <span class="post">Верстка сайтов</span>
            </div>
          </div>
        </div>
      </section>
      <section class="projects">
        <div class="title">Проекты & Playground</div>
        <div class="projects">
          <div class="project project-1">
            <a href="https://wamdy18.github.io/restaurant/" target="_blank">
              <img src="../assets/site1.png" alt="">
            </a>
            <a href="https://github.com/Wamdy18/restaurant" target="_blank">Github Link</a>
          </div>
          <div class="project project-2">
            <a href="https://wamdy18.github.io/utc/" target="_blank">
              <img src="../assets/site2.png" alt="">
            </a>
            <a href="https://github.com/Wamdy18/utc" target="_blank">Github Link</a>
          </div>
        </div>
      </section>
      <section class="contacts">
        <div class="title">контакты</div>
        <div class="contacts-info">
          <span>+7 999 562 19 05 (номер телефона, WhatsApp)</span>
          <a href="https://t.me/wamdy18"><span>@Wamdy18 (telegram)</span></a>
          <a href="https://vk.com/letsinspire"><span>ВКонтакте</span></a>
        </div>
      </section>
    </div>
    <footer>
      Copyright (c) Vladimir Petrov, 2024
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
  },
};
</script>

<style>
section.first {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}
.home {
  padding-top: 20px;
  font-family: 'Roboto', sans-serif;
}
.container {
  padding-inline: 50px;
}
.slogan {
  color: #868686;
  font-weight: 100;
  font-size: 18px;
  text-align: right;
}
.greetings {
  color: #868686;
  font-weight: 100;
  font-size: 18px;
}
h1 {
  font-weight: 300;
  font-size: 120px;
}
.title {
  font-size: 14px;
  color: white;
  text-transform: uppercase;
  background-color: #000;
  padding: 8px 16px;
  border-radius: 20px;
  display: inline;
  font-weight: 100;
}
.about-me {
  text-align: center;
  margin-top: 40px;
}
.about-me p {
  font-weight: 300;
  font-size: 24px;
  line-height: 32px;
}
.skills {
  margin-top: 50px;
}
.skills > span {
  font-weight: 100;
  margin-top: 15px;
  display: block;
}
.skills > div {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
  margin-top: 15px;
}
.skill {
 font-weight: 100;
 font-size: 16px;
 padding: 8px 16px;
 border: .2px solid #000;
 border-radius: 16px;
}
section.experience, section.projects, section.contacts {
  margin-top: 70px;
}
.exp-items {
  margin-top: 50px;
  display: flex;
  /* justify-content: center; */
  align-items: center;
  flex-direction: column;
  gap: 30px;
}
.exp-item {
  display: flex;
  align-items: center;
  min-width: 500px;
}
.vline {
  width: 2px;
  background-color: orange;
  height: 80px;
  margin-right: 20px;
}
.exp-item .year {
  font-weight: 300;
  font-size: 14px;
}
.exp-item .info {
  display: flex;
  flex-direction: column;
}
.exp-item .info .org, .exp-item .info .post {
  font-weight: 100;
  margin-top: 8px;
  font-size: 14px;
}
div.projects {
  margin-top: 50px;
  display: flex;
  justify-content: space-between;
}
div.projects img {
  max-width: 45vw;
  filter: grayscale(100%);
  transition: all 0.3s ease;
  margin-bottom: 15px;
}
div.projects .project img:hover {
  filter: grayscale(0%);
  transform: scale(1.05);
}
div.projects .project a {
 text-decoration: none;
 text-transform: uppercase;
 color: black;
 font-weight: 300;
 font-size: 16px;
}
.contacts-info {
  display: flex;
  flex-direction: column;
  gap: 15px;
  margin-top: 50px;
  text-align: center;
  font-weight: 300;
  font-size: 16px;
}
.contacts-info a {
  text-decoration: none;
  color: #000;
}
footer {
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 14px;
  font-weight: 100;
  background-color: #000;
  color: white;
  margin-top: 50px;
}

/* responsive */
@media (max-width:  1200px) {
  h1 {
    font-size: 100px;
  }
}
@media (max-width:  1024px) {
  h1 {
    font-size: 80px;
  }
  div.projects img {
    max-width: 100%;
  }
  div.projects {
    gap: 20px;
  }
}
@media (max-width:  900px) {
  h1 {
    font-size: 70px;
  }
  section.first {
    height: 70vh;
  }
}
@media (max-width:  768px) {
  h1 {
    font-size: 60px;
  }
  .container {
    padding-inline: 20px;
  }
  .about-me p {
    font-size: 18px;
    line-height: 22px;
    }
    div.projects img {
      filter: grayscale(0%);
    }
    div.projects .project img:hover {
      transform: scale(1);
    }
}
@media (max-width:  600px) {
  h1 {
    font-size: 60px;
  }
  .exp-items {
    align-items: start;
  }
  .exp-item {
    min-width: auto;
  }
}
@media (max-width:  480px) {
  h1 {
    font-size: 50px;
  }
  .about-me p {
  font-size: 16px;
  line-height: 20px;
  }
  div.projects {
    flex-direction: column;
    gap: 50px;
  }
}
@media (max-width:  320px) {
  h1 {
    font-size: 40px;
  }
}

</style>
