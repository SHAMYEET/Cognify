🤖 Prep AI
Your Personal AI Interview Coach

Prep AI is a web-based application designed to help users practice for behavioral interviews by providing AI-generated questions and constructive feedback. Built for a fast-paced hackathon, this tool leverages the power of Google's Gemini API to create a realistic and helpful interview preparation experience.

✨ Features
🤖 AI-Generated Questions: Get unique, high-quality behavioral interview questions on demand.

💡 Instant Feedback: Submit your answers and receive an immediate, concise summary of your performance.

📊 Detailed Analysis: Option to get in-depth feedback based on the STAR (Situation, Task, Action, Result) method.

📱 Responsive Design: A clean, modern, and fully responsive layout that works on both desktop and mobile.

🌗 Smart Theming: Automatically detects your system's preferred theme (light/dark) and allows you to toggle between them.

🎬 Interactive Experience: UI elements like text streaming and smart button states create a smooth, app-like feel.

🚀 Tech Stack
🛠️ Getting Started
To run this project locally, follow these simple steps:

Clone the repository (or download the files).

Place the files index.html, style.css, and script.js in the same folder.

Open index.html in your favorite web browser.

That's it! The application is fully self-contained and requires no build steps or installations.

⚙️ How It Works
The user clicks "Start Interview" to initiate the process.

A call is made to the Gemini API to fetch a behavioral question. The prompt is engineered to request concise, plain-text questions.

The user types their answer into the text area.

Upon submitting, the user's answer and the original question are sent back to the Gemini API with a system prompt that instructs the AI to act as an interview coach and provide feedback.

The initial feedback is displayed, and an option for more detailed, STAR-based feedback becomes available.

The entire user flow is managed with robust error handling, including an exponential backoff strategy to handle temporary API overloads.

🔮 Future Improvements
[1] Session History: Store past questions and feedback for users to review.

[2] Question Categories: Allow users to select specific types of questions (e.g., Leadership, Teamwork).

[3] Voice-to-Text: Re-implement speech recognition for a hands-free experience.

[4] User Accounts: Add user authentication to save progress across devices.
