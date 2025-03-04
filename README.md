# 🔍 Type Ahead (Live Search)  

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)  
![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5)  
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)  

🔎 **Type Ahead** is a **real-time search suggestion tool** that dynamically filters and displays **matching results** as you type. It uses **fetch API** to retrieve a dataset of cities and states, and highlights matched text in search results.  

---

## 📌 Features  
✅ **Instant search suggestions** as the user types  
✅ **Fetch API** to retrieve a dataset dynamically  
✅ **Highlight matching text** in search results  
✅ **Efficient filtering using JavaScript's `.filter()` and `.map()` methods**  
✅ **Smooth UI updates** with event listeners  

---

## 🛠️ Tech Stack  

🔹 **JavaScript (ES6+)** – Fetch API, event listeners, string manipulation  
🔹 **HTML5** – Structuring the UI  
🔹 **CSS3** – Styling & highlight effects  

---

## 🎯 How It Works  
1. **Fetch Data**: A dataset of **cities & states** is fetched from an external source.  
2. **Filter Data**: As the user types, the input is matched against city/state names.  
3. **Highlight Matches**: Matching parts of the text are highlighted.  
4. **Display Results**: The UI updates dynamically with matching entries.  

---

## 📂 Project Setup  

1. **Clone this repository**  
   ```sh
   git clone https://github.com/JawadAhmed1402/6)-Type-Ahead.git
      
2. **Navigate into the project folder**      
   ```sh
   cd 6)-Type-Ahead      
   
3. Open **index.html** in your browser or use Live Server       

## 📝 Sample Code (JS) 

    ```sh
      const endpoint = 'https://gist.githubusercontent.com/jshawl/17f1bfb09e342437f7a046df64b02b1e/raw/us-cities.json';
      const cities = [];
      fetch(endpoint)
        .then(response => response.json())
        .then(data => cities.push(...data));
      function findMatches(wordToMatch, cities) {
          return cities.filter(place => {
          const regex = new RegExp(wordToMatch, 'gi'); 
          return place.city.match(regex) || place.state.match(regex);
         });        
      }     
      const searchInput = document.querySelector('.search');       
      const suggestions = document.querySelector('.suggestions');       
      searchInput.addEventListener('input', displayMatches);

## 👨‍💻 Contributing

Contributions are **welcome!** 🚀        
Feel free to **open an issue** or **submit a pull request** to improve this project.         

## 🧑‍💻 Author

👤 Jawad Ahmed      
🔗 [GitHub Profile](https://github.com/JawadAhmed1402/)        

## 📬 Connect with Me       


## 💬 Feel free to connect, share feedback, or collaborate! 🚀
