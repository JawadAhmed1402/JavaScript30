# 🏋️‍♂️ JavaScript Array Cardio (Day 1)  

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)  
![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5)  
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)  

📊 A JavaScript **practice session** focused on **Array methods** like `.map()`, `.filter()`, `.reduce()`, `.sort()`, and more!  

## 📌 Features  
✅ Hands-on practice with **essential JavaScript array methods**  
✅ Uses **real-world datasets** for better learning  
✅ Outputs results in the **developer console**  
✅ Clean and simple **JavaScript code**  

## 🛠️ Technologies Used  
- **JavaScript (ES6+)** – Array methods, console output  
- **HTML5** – Basic structure for running the script  
- **CSS3** – Simple styling  

## 🎯 Array Methods Covered  
✅ **`.filter()`** – Filters an array based on a condition  
✅ **`.map()`** – Transforms array elements  
✅ **`.sort()`** – Sorts array elements  
✅ **`.reduce()`** – Reduces an array to a single value  
✅ **`.some()` / `.every()`** – Checks conditions in an array  
✅ **`.find()` / `.findIndex()`** – Finds elements based on a condition  

## 📂 Project Setup  
1. **Clone this repository**  
   ```sh
   git clone https://github.com/JawadAhmed1402/4)-Array-cardio-Day-1.git      
2. **Navigate into the project folder**      
   ```sh
   cd 4)-Array-cardio-Day-1       
3. **Open index.html in your browser**
4. **Open Developer Console (F12 > Console) to see results**
   
## 📝 Sample Code (JS)
   ```sh
   // Sample dataset
   const people = [
   { name: "John", year: 1988 },
   { name: "Jane", year: 1995 },
   { name: "Sam", year: 2001 },
   { name: "Sara", year: 1975 }
   ];

   // Filter: People born before 1990
   const olderPeople = people.filter(person => person.year < 1990);
   console.table(olderPeople);

   // Map: Extract names from the dataset
   const names = people.map(person => person.name);
   console.log(names);

   // Sort: By birth year
   const sortedPeople = people.sort((a, b) => a.year - b.year);
   console.table(sortedPeople);

## 💬 Feel free to connect, share feedback, or collaborate! 🚀
   
