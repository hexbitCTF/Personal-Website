# 🌐 Personal Website — Hexbit  

> Source code for my personal website hosted at  
> https://hexbitctf.github.io/Personal-Website/  

A minimal and modern web page built to showcase my profile, CV, and personal/work links — all presented with an interactive background powered by particles.js.  

---

## ✨ Features  

- 🎆 Particles.js Integration — Animated, interactive particle background.  
- 🧭 Clean & Responsive Design — Works on desktop and mobile.  
- 🔗 Personal & Work Links — Quick access to portfolio, GitHub, social links, and CV.  
- 🖼️ Profile Section — Displays a profile picture and short bio.  
- ⚡ Lightweight — Pure HTML, CSS, and vanilla JavaScript. No frameworks.  

---

## 🛠️ Tech Stack  

- HTML5  
- CSS3  
- JavaScript (ES6)  
- Particles.js  

---

## 🚀 Getting Started  

You can view the live version here:  
👉 https://hexbitctf.github.io/Personal-Website/  

Or to run it locally:  

### 1. Clone the repository  
git clone https://github.com/HexbitCTF/Personal-Website.git  
cd Personal-Website  

### 2. Open in your browser  
Simply open index.html in your web browser.  
No server or build process is required.  

---

## 🧩 Customization  

This project is designed to be easily customizable.  
You can adjust the layout, styling, and particle effects with minimal effort.  

### index.html  
- Update your name, bio, and personal/work links.  
- Replace the profile picture with your own (img/profile.jpg or custom path).  
- Modify the particle configuration if embedded inline or via particles.json.  

### style.css  
- Change fonts, colors, or layout.  
- Customize buttons, hover effects, and responsive breakpoints.  
- Add or remove visual elements (cards, icons, etc.).  

### particles.json (optional)  
If your site uses an external config file, you can tweak:  
- particles.number.value → particle count.  
- particles.color.value → particle color.  
- particles.move.speed → movement speed.  
- interactivity.events.onhover → hover interaction type.  

Example snippet:  

{  
  "particles": {  
    "number": { "value": 80 },  
    "color": { "value": "#00ffff" },  
    "move": { "speed": 3 },  
    "line_linked": { "enable": true, "opacity": 0.4 }  
  },  
  "interactivity": {  
    "events": { "onhover": { "enable": true, "mode": "repulse" } }  
  }  
}  

---

## 📁 Suggested File Structure  

Personal-Website/  
├── index.html  
├── style.css  
├── particles.json  
├── img/  
│   └── profile.jpg  
├── files/  
│   └── CV.pdf  
└── LICENSE  

---

## 🧠 About  

Created by Hexbit as a clean and visually appealing personal landing page.  
It serves as a digital profile that includes links to work, social accounts, and a downloadable CV — enhanced by an interactive particle effect for a touch of personality.  

The site is intentionally lightweight, requiring no frameworks or dependencies — just HTML, CSS, and JavaScript.  
It’s perfect as a base template for your own personal page.  

---

## 🧰 Tips  

- Add alt text to your profile image for accessibility.  
- Compress and resize large images for faster load times.  
- Use defer or async for JavaScript files to improve performance.  
- Optionally, host the site with a custom domain using GitHub Pages.  

---

## 🙌 Contributing  

If you have improvements or new particle presets, feel free to:  
1. Fork this repository  
2. Make your changes  
3. Submit a pull request  

---

## 📄 License  

This project is licensed under the MIT License.  
You’re free to use, modify, and share it with proper attribution.  

MIT License  

Copyright (c) 2025 Hexbit  

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the “Software”), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.  

---

## 🌟 Live Preview  

🔗 Website: https://hexbitctf.github.io/Personal-Website/  
📂 Repository: https://github.com/HexbitCTF/Personal-Website  

---

## 💬 Contact  

If you’d like to connect, collaborate, or suggest improvements — feel free to reach out or open an issue on the repo.  

✨ Built with simplicity and passion by Hexbit.  
