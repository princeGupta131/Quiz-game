
 🧠 Deadly Questions Quiz Game  

A minimalist, interactive quiz game built with HTML, CSS, and JavaScript. Test your knowledge with randomized trivia questions!  

---
 🖥️ Screenshots  
| Question Screen | Correct Answer |  
|----------------|----------------|  
| ![Question]([quiz-screenshot1.png](https://github.com/princeGupta131/Quiz-game/blob/main/Screenshot_2025-06-21-15-53-59-73_f9a7afa717ced9e1fc9be9833291031a.jpg)) | ([quiz-screenshot2.png](https://github.com/princeGupta131/Quiz-game/blob/main/Screenshot_2025-06-21-15-54-06-53_f9a7afa717ced9e1fc9be9833291031a.jpg)
| 
 🛠️ How It Works  
1. Click **"Start"** to load a random question  
2. Choose an answer:  
   - ✅ **Green border** = Correct  
   - ❌ **Red border** = Incorrect  
3. Press **"Next"** for a new question  


🚀 Installation  
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/quiz-game.git
   ```
2. Open `index.html` in any browser  

📚 Customization  
Add Your Own Questions  
Edit `learning.js`
```javascript
const questions = [
  {
    question: "Your question here",
    answers: ["Option 1", "Option 2", "Option 3", "Option 4"],
    correctAnswer: "Option 1"
  }
  // Add more...
];
```

### Styling  
Modify `learning.css`:  
```css
.options {
  background-color: #your-color; /* Change button colors */
  border: 2px dashed #custom-border; 
}
```

---

🌟 Why This Project?  
- Perfect for learning DOM manipulation  
- Easy to extend (add timers, score tracking, etc.)  
- Portfolio-ready- Demonstrates core JS skills  

---

🤝 Contributing  
PRs welcome! Ideas:  
- Add a scoring system  
- Implement question categories  
- Create a high-score leaderboard  

---

📜 License  
MIT © [princeGupta

