# ⏰ JavaScript Clock  

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)  
![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5)  
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)  

🕰️ A **real-time analog clock** built using **JavaScript, HTML, and CSS**. The clock updates dynamically every second, just like a real one!  

## 📌 Features  
✅ **Analog clock with moving hands**  
✅ **Real-time updates** every second  
✅ **Smooth transitions** using CSS  
✅ Uses **Date object** to get the current time  
✅ Fully **responsive design**  

## 🛠️ Technologies Used  
- **JavaScript (ES6+)** – Fetching current time and updating clock hands  
- **HTML5** – Structuring the clock face  
- **CSS3** – Styling and smooth animations  

## 🎯 How It Works  
1. The script fetches the **current time** using JavaScript’s `Date()` object  
2. It calculates the **rotation angles** for the **hour, minute, and second hands**  
3. The clock hands **rotate smoothly** using CSS transitions  
4. The time updates **every second**  

## 📂 Project Setup  
1. **Clone this repository**  
   ```sh
      git clone https://github.com/JawadAhmed/2)-JS-and-CSS-Clock.git     
2. **Navigate into the project folder**
   ```sh
      cd 2)-JS-and-CSS-Clock.git   

## 📝 Code Overview
**• index.html** – Defines the clock face and hands   
**• style.css** – Adds styles and animations for smooth clock hand movement   
**• script.js** – Calculates and updates the hand positions every second     

## 🕰️ Sample Code (JS)
   ```sh
      function setClock() {
         const now = new Date();
         const seconds = now.getSeconds();
         const minutes = now.getMinutes();
         const hours = now.getHours();

         const secondDeg = ((seconds / 60) * 360) + 90;
         const minuteDeg = ((minutes / 60) * 360) + 90;
         const hourDeg = ((hours / 12) * 360) + 90;

         document.querySelector(".second-hand").style.transform = `rotate(${secondDeg}deg)`;
         document.querySelector(".minute-hand").style.transform = `rotate(${minuteDeg}deg)`;
         document.querySelector(".hour-hand").style.transform = `rotate(${hourDeg}deg)`;
      }
     setInterval(setClock, 1000);
     setClock(); // Initialize clock immediately

## 💬 Feel free to connect, share feedback, or collaborate! 🚀


