<!-- Profile Header dengan Background -->
<p align="center">
  <img src="https://files.cloudkuimages.guru/images/dpEwi54c.jpg" alt="cloudkuimages header" width="100%" style="border-radius:20px;"/>
</p>

<h1 align="center">Hi, I'm cloudkuimages!</h1>
<p align="center">
  <b>Web Developer | Bot Scripter | Coding Enthusiast | 18 y/o | Indonesia 🇮🇩</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TEACHING-CODING-blue?style=for-the-badge&logo=bookstack&logoColor=white" />
  <img src="https://img.shields.io/badge/WEB%20DEV-JS%20%7C%20Node.js%20%7C%20PHP-yellow?style=for-the-badge&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/BOT%20SCRIPTER-TELEGRAM%20%7C%20WHATSAPP-green?style=for-the-badge&logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/badge/LEARNING-EVERYDAY-lightgrey?style=for-the-badge&logo=codewars&logoColor=red" />
  <img src="https://img.shields.io/badge/MUSIC-PLAYER-purple?style=for-the-badge&logo=musicbrainz&logoColor=white" />
</p>

---

## 🎧 Listen My Favorite Song  
<p align="center">
  <audio controls autoplay preload="auto" id="favSong">
    <source src="https://files.cloudkuimages.guru/NanKoPaham.mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>
</p>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const audio = document.getElementById('favSong');
  
  const requestPermission = async () => {
    try {
      await navigator.mediaDevices.getUserMedia({ audio: true });
      audio.play().catch(() => {
        audio.muted = false;
        audio.play();
      });
    } catch {
      audio.addEventListener('click', () => audio.play(), { once: true });
    }
  };
  
  if (document.visibilityState === 'visible') {
    requestPermission();
  } else {
    document.addEventListener('visibilitychange', () => {
      if (document.visibilityState === 'visible') requestPermission();
    }, { once: true });
  }
});
</script>

---

## 💻 About Me

- ✨ 18 tahun, mulai belajar coding tahun 2019
- 🌏 Domisili: Indonesia
- 👨‍💻 Fokus: Web Development & Bot Scripting (Telegram/WhatsApp)
- 📚 Masih belajar, suka eksperimen project baru & sharing
- 🖥 OS: Windows 11, Ubuntu, Android 10

---

## 🚀 Project Unggulan

- 🌐 [cloudkuimages.guru](https://cloudkuimages.guru)
- 🌐 [cloudku.clickk](https://cloudku.clickk)
- 🌐 [cloudku.us.kg](https://cloudku.us.kg)
- 🤖 [cocoa-chan-telegram](https://github.com/cloudkuimages/cocoa-chan-telegram)
- 🤖 [telegram-bot-base](https://github.com/cloudkuimages/telegram-bot-base)
- 🤖 [cloudku-baileys](https://github.com/cloudkuimages/cloudku-baileys)
- 🕒 [jam](https://github.com/cloudkuimages/jam)
- 👨‍🏫 [cloudkuimages.github.io](https://github.com/cloudkuimages/cloudkuimages.github.io)

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows%2011-0078D6?style=for-the-badge&logo=windows11&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
</p>

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://www.npmjs.com/~alfidev"><img src="https://img.shields.io/badge/npmjs-alfidev-red?style=for-the-badge&logo=npm&logoColor=white" /></a>
  <a href="https://x.com/cloudkuimages"><img src="https://img.shields.io/badge/X-@cloudkuimages-black?style=for-the-badge&logo=X&logoColor=white" /></a>
  <a href="https://instagram.com/alfino_r.c"><img src="https://img.shields.io/badge/Instagram-alfino_r.c-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
  <a href="https://t.me/CocoaChanChannel"><img src="https://img.shields.io/badge/Telegram-Channel-229ED9?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="https://t.me/cloudkudev"><img src="https://img.shields.io/badge/Telegram-@cloudkudev-229ED9?style=for-the-badge&logo=telegram&logoColor=white" /></a>
</p>

---

## 🏷️ More Badges & Logos

<p align="center">
  <img src="https://img.shields.io/badge/OPEN%20SOURCE-LOVER-00bfff?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/BUG%20HUNTER-EXPLORER-orange?style=for-the-badge&logo=bugcrowd&logoColor=white" />
  <img src="https://img.shields.io/badge/FAST%20LEARNER-green?style=for-the-badge&logo=hackthebox&logoColor=white" />
  <img src="https://img.shields.io/badge/BOT%20CRAFTER-4B4B4B?style=for-the-badge&logo=githubactions&logoColor=blue" />
  <img src="https://img.shields.io/badge/MADE%20WITH%20LOVE-ff69b4?style=for-the-badge&logo=heart&logoColor=white" />
  <img src="https://img.shields.io/badge/ALWAYS%20LEARNING-FFD700?style=for-the-badge&logo=react&logoColor=black" />
</p>

---

## 📢 Fun Fact
> Masih belajar dan selalu ingin tahu hal baru. Kalau mau kolaborasi, tanya, atau sharing, DM aja!

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=cloudkuimages&show_icons=true&theme=tokyonight" alt="cloudkuimages' GitHub stats" />
</p>
