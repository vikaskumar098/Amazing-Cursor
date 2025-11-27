
<!-- HEADER -->
<h1 align="center">🎥✨ Amazing Cursor – Interactive Spotlight Effect</h1>
<p align="center">
  A cinematic spotlight cursor effect on fullscreen video using HTML, CSS & JavaScript.
</p>

<!-- BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/HTML-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

<!-- LINKEDIN BADGE -->
<p align="center">
  <a href="https://www.linkedin.com/in/vikas0905/" target="_blank">
    <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

## 🔗 **Important Links**
<p align="center">
  <a href="https://github.com/vikaskumar098/Amazing-Cursor.git" target="_blank">
    <img src="https://img.shields.io/badge/🔍 View%20Source%20Code-000000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://vikaskumar098.github.io/Amazing-Cursor/" target="_blank">
    <img src="https://img.shields.io/badge/🚀 Live%20Demo-0A66C2?style=for-the-badge&logo=githubpages&logoColor=white"/>
  </a>
</p>

---

## 🌟 **Preview**
A spotlight follows your cursor, revealing the video below with a smooth cinematic lighting effect.

---

## ✨ **Features**
- 🎥 Fullscreen overlapping video  
- 🖱 Spotlight follows your mouse  
- 🌘 Smooth radial gradient effect  
- ⚡ Pure Vanilla JavaScript  
- 🧭 Responsive and lightweight  
- 🎨 Modern cinematic UI  

---

## 📂 **Project Structure**
```

Amazing Cursor/
│── index.html
│── style.css
│── script.js
└── war.mp4

````

---

## 🧠 **How It Works**

### 🟨 JavaScript – Track Cursor Position
```js
addEventListener("mousemove", (e) => {
    document.body.style.setProperty("--x", e.clientX + "px");
    document.body.style.setProperty("--y", e.clientY + "px");
});
````

---

### 🔵 CSS – Spotlight Gradient

```css
background: radial-gradient(120px at var(--x) var(--y),
 rgba(219, 224, 219, 0),
 rgba(40, 40, 44, 0.85));
```

---

### 🔴 HTML Layout

```html
<video autoplay loop muted src="war.mp4"></video>
<div class="div"></div>
```

---

## 🚀 **Run Locally**

1. Clone repo

   ```
   git clone https://github.com/vikaskumar098/Amazing-Cursor.git
   ```
2. Open `index.html`
3. Move your cursor → enjoy the effect!

---



## 🛠 Tech Stack

* HTML5
* CSS3
* JavaScript (Vanilla)

---

## 🔮 Future Improvements

* 🌈 Multicolor spotlight
* 🧊 Frosted glass glow
* 🔥 Neon cyberpunk effect
* 🎨 Custom cursor image

---

## 👨‍💻 **Author – Vikas Kumar**

<p align="center">
  <a href="https://www.linkedin.com/in/vikas0905/" target="_blank">
    <img src="https://img.shields.io/badge/Visit%20My%20LinkedIn%20Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

<p align="center">⭐ If you like this project, kindly star the repository!</p>

<p align="center">Made with ❤️ by Vikas Kumar</p>


