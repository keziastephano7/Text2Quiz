# 📚 Text2Quiz

**Text2Quiz** is an AI-powered quiz generator that transforms any text into engaging, customizable quizzes using Google Gemini AI. Perfect for students and educators!

---

## 📌 Features

- **AI Quiz Generation**: Paste any text and instantly generate quizzes using **Google Gemini AI**.
- **Customizable Questions**: Choose 5, 10, 15, or 20 questions based on input length.
- **Multiple Choice**: Each question includes 4 options with one correct answer.
- **User Authentication**: Secure login/signup with **Firebase Authentication**.
- **Personalized Dashboard**: Save prompts, view quiz history, and track quiz attempts.
- **Quiz History**: Review previous quizzes and see your answers vs. the correct ones.

---

## 📌 Tech Stack

- **Flutter** – UI Framework  
- **Dart** – Logic  
- **Firebase** – Auth, Firestore, Storage  
- **Google Gemini AI** – Quiz Generation  

---

## 📌 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Text2Quiz.git
cd Text2Quiz
```

### 2. Install Dependencies
```bash
flutter pub get
```

3. Set Up Environment Variables
Create a .env file in the project root:

```env
GEMINI_API_KEY=your_gemini_api_key
```

4. Configure Firebase
Use the provided firebase_options.dart or run:

```bash
flutterfire configure
```
Make sure to enable Authentication and Firestore in your Firebase Console.

5. Run the App
```bash
flutter run
```

---

## 📌 Usage
Sign Up / Log In – Use your email and password.

Paste Text – Enter any text (e.g., article, notes).

Generate Quiz – Click Generate Quiz.

Take Quiz – Answer, submit, and get instant feedback.

View History – Review past quizzes and results.

---

## 📁 Project Structure
```plaintext
lib/
 ├── auth_page.dart           # Login & Signup UI
 ├── dashboard_page.dart      # Dashboard & quiz generator
 ├── quiz_page.dart           # Quiz-taking UI
 ├── attempted_quiz_page.dart # View past attempts
 ├── firebase_options.dart    # Firebase config
 └── ...
```

---

## 🔒 Security
User data is securely stored in Firestore under each user's UID.

Authentication handled by Firebase Auth.

---
