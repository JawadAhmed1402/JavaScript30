# 🎨 CSS Variables & JavaScript  

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)  
![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5)  
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)  

✨ A fun interactive project where **JavaScript dynamically updates CSS variables** in real-time. Adjust **spacing, blur, and color** using input sliders!  

## 📌 Features  
✅ **Adjust spacing, blur, and color** in real-time  
✅ Uses **CSS variables (`--variable`)** for live updates  
✅ **Interactive sliders** to control properties  
✅ Smooth UI updates with **event listeners**  
✅ Fully **responsive design**  

## 🛠️ Technologies Used  
- **JavaScript (ES6+)** – Event listeners, DOM manipulation  
- **CSS3** – Variables, transitions, styling  
- **HTML5** – Structuring the UI  

## 🎯 How It Works  
1. The **CSS variables** (`--spacing`, `--blur`, `--color`) define styling properties  
2. JavaScript listens for **slider input changes**  
3. Updates **CSS variables dynamically**, applying changes instantly  

## 📂 Project Setup  
1. **Clone this repository**  
   ```sh
   git clone https://github.com/JawadAhmed1402/3)-CSS-variable-and-JS.git
2. **Navigate into the project folder**       
   ```sh
   cd 3)-CSS-variable-and-JS    
3. **Open index.html in your browser or use Live Server**   

## 📝 Code Overview    
• **index.html** – Contains input sliders for spacing, blur, and color   
• **style.css** – Defines CSS variables and styling       
• **script.js** – Listens for input changes and updates CSS variables    

## 🎨 Sample Code (JS)
   ```sh
   const inputs = document.querySelectorAll("input");

   function handleUpdate() {
     const suffix = this.dataset.sizing || ""; // Get "px" for spacing & blur
     document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);
   }

   inputs.forEach(input => input.addEventListener("input", handleUpdate));

## 💬 Feel free to connect, share feedback, or collaborate! 🚀





   
   
   
