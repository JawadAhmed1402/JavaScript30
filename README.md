# 🥁 Drum Kit  

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)  
![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5)  
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)  

🎶 A fun and interactive **drum kit** built using **JavaScript, HTML, and CSS**. Press different keyboard keys to play unique drum sounds!  

## 📌 Features  
✅ Play drum sounds using **keyboard keys**  
✅ Visually highlights the keys when pressed  
✅ Uses **event listeners** for keyboard input  
✅ **Audio files** are preloaded for instant sound playback  
✅ Simple, **responsive design**  

## 🛠️ Technologies Used  
- **JavaScript (ES6+)** – Event listeners, audio playback  
- **HTML5** – Structure for the drum kit layout  
- **CSS3** – Styling and animations  

## 🎯 How It Works  
1. Press the **corresponding keys** on your keyboard (e.g., A, S, D, F, etc.)  
2. The key will **light up** and play a unique drum sound  
3. The effect resets, allowing continuous play   

## 📂 Project Setup  
1. **Clone this repository**  
   ```sh
   git clone https://github.com/yourgithubusername/Drum-Kit.git

## 📝 Code Overview
**index.html** – Defines the drum buttons with assigned keys   
**style.css** – Adds styles and animations for keypress effects   
**script.js** – Listens for key events and plays corresponding sounds   

## 🎵 Sample Code (JS)
   ```window.addEventListener("keydown", function (e) {   
  const audio = document.querySelector(`audio[data-key="${e.keyCode}"]`);   
  const key = document.querySelector(`.key[data-key="${e.keyCode}"]`);   
  
  if (!audio) return; // Stop function if key is not assigned   

  audio.currentTime = 0; // Rewind sound to start    
  audio.play();    
  key.classList.add("playing");     
  
  setTimeout(() => key.classList.remove("playing"), 100);      
});    


## 💬 Feel free to connect, share feedback, or collaborate! 🚀
