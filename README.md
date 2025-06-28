<style>
   :root {
      --primary-color: #40c6d0;
      --secondary-color: #5759ee;
      --main-gradient: linear-gradient(45deg, var(--primary-color) 0%, var(--secondary-color) 100%);
   }

   h1,h2 {
      border-bottom: 0px;
      position: relative;
      margin-top: 0 !important;
      margin-bottom: 30px !important;
      padding: 10px 0 !important;
   }

   h1::before,h2::before{
      content: "";
      position: absolute;
      width: 100%;
      height: 1px;
      background: var(--main-gradient);
      bottom: 0;
      left: 0;
      opacity: 0.2;
   }

   .logo {
      opacity: 0;
      transform: translateY(-5px);
      animation: transform 1s ease 1s forwards;
   }

   .color-gradient {
      color: transparent;
      background: var(--main-gradient);
      -webkit-background-clip: text;
      background-clip: text;
   }

   @keyframes transform {
      100% {
         opacity: 1;
         transform: translateY(0);
      }
   }
</style>

<div class="logo" align="center">
  <img width="300" src="https://raw.githubusercontent.com/FrontElf/FrontElf/refs/heads/main/logo.png" />
</div>

<h1  align="center">Greetings! 👋</h1>

<h3 align="center">
I'm a web developer who loves creating modern and user-friendly websites
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white" />  
  <img src="https://img.shields.io/badge/-SCSS-CC6699?style=flat&logo=sass&logoColor=white" />
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/-PHP-777BB4?style=flat&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/-WordPress-21759B?style=flat&logo=wordpress&logoColor=white" />
</p>

##

<p>
🌐 Currently working on: responsive landing pages and web applications using modern technologies
</p>

<p>
🌱 Learning: actively exploring new tools and improving my skills in React and WordPress
</p>

<p>
👯 Looking for collaboration: with other developers and designers to create amazing projects together!
</p>

##
<h2 class="color-gradient" align="center">
✨ "Let's code the future together!" ✨
</h2>


