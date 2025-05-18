Flashcard Quiz App

A stylish and interactive web-based flashcard quiz game that fetches trivia questions from the [Open Trivia Database API](https://opentdb.com/). Users can test their knowledge by flipping flashcards, selecting answers, and tracking their score in real-time.

🌟 Features

- 🎴 Flip-style flashcards (Question on front, Answer on back)
- 🎯 Real-time score and progress tracking
- 🧠 Multiple trivia categories and difficulty levels
- ⚡ Live question fetching via public trivia API
- 🎨 Responsive, modern UI with engaging design
- 🔁 Reset functionality to start a new session

🚀 Getting Started
To run the app locally:
1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.

That's it! No installation or server required.

🧩 Usage

- Select a Category and Difficulty using the dropdown filters (optional).
- Click the card to flip between the question and answer.
- Click "Know ✅" if you knew the answer (score increases).
- Click "Don’t Know ❌" to skip without increasing score.
- Click "Reset Score" to restart the quiz session.

🧠 Tech Stack

- HTML5 – Structure
- CSS3 – Styling (including custom fonts and animations)
- JavaScript (ES6) – Logic and API interaction
- Open Trivia DB API – Live question data source

🔧 Code Highlights

- Dynamic Data: Questions are fetched from an API, not hardcoded.
- UI Interactions: Card flipping, dropdown filtering, score updating, and loading spinner.
- Modular Script: Self-contained IIFE (Immediately Invoked Function Expression) for cleaner scoping.

📦 API Reference

Endpoint Used:  
https://opentdb.com/api.php?amount=1&type=multiple

Optional parameters:
- Category : ID for specific trivia category
- Difficulty : easy, medium, hard

Full API documentation: https://opentdb.com/api_config.php

📁 File Structure

📦 flashcard-quiz-app/
┣ 📄 index.html # Main HTML + embedded CSS & JS

> You can optionally separate CSS and JS into separate files for scalability.

✨ Fonts Used

- Anton
- Fredoka
- Roboto Mono
- Patrick Hand
- Orbitron  
(Imported from Google Fonts)

📌 Todo / Future Improvements

- Add timer and streak system
- Allow multiple choice options (not just flashcards)
- Save high scores with local storage
- Responsive design tweaks for smaller screens

---

Made with 💡 and 🧠 by Aryan Singh [ ELECTROX ]
