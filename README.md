# 🎯 QuizApp

QuizApp is a ReactJS-based web application that allows users to take assessments by solving multiple-choice questions (MCQs). The application ensures a seamless user experience with validations, scoring, and a final result display.

---

## ✨ Features

- **Interactive Quiz**: Users can solve MCQs one question at a time.  
- **Option Selection Validation**: Users cannot proceed to the next question without selecting an option.  
- **Dynamic Scoring**: Scores are calculated in real-time using a score state variable.  
- **Final Score Display**: Once all questions are answered, users are presented with their final score.  
- **User-Friendly Interface**: Smooth and intuitive interface for taking quizzes.  

---

## 🚀 How It Works

### 1. Start the Quiz  
The quiz begins with the first question displayed on the screen.

### 2. Option Selection  
Users must select an option to enable the **Next** button.  
If no option is selected, users cannot proceed to the next question.

### 3. Score Calculation  
The score is updated dynamically based on the correctness of the selected option.

### 4. Final Score  
Once all questions are completed, the application displays the final score out of the total number of questions.

---

## 🛠️ Technologies Used

- **ReactJS**: Frontend framework for building the user interface  
- **State Management**: Managed using React's `useState` and `useEffect` hooks  
- **CSS**: For styling the application  

---

## 📸 Screenshot

![QuizApp Screenshot](./Screenshot%20(673).png)

> _Note: Make sure the screenshot image is placed in the project directory where this README file exists. If it's in a subfolder, adjust the path accordingly._

---

## 📂 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Kiran-ls/React-QuizApp
