# Life-Compass-Dashboard

🧭 Life Compass Dashboard
A holistic daily dashboard built with HTML, CSS (Tailwind CSS), and JavaScript that helps you track your mood, manage tasks, focus with a Pomodoro timer, check the weather, and get daily inspiration.

💡 Concept
The Life Compass Dashboard aims to provide a centralized, easy-to-use interface for managing various aspects of your daily well-being and productivity. It brings together essential tools and information to help you stay mindful, organized, and motivated.

🔧 Features
Daily Mood Log: Track your daily mood using a selection of emojis. Your mood for the day is saved locally.

To-Do List: A simple and effective task manager. Add new tasks, mark them as complete, and delete them. All tasks are saved in your browser's LocalStorage.

Pomodoro Timer: A classic productivity timer with 25-minute work sessions and 5-minute break sessions to help you focus and manage your time effectively.

Weather Display: Shows current weather conditions for a default city (London) due to browser security restrictions on geolocation in this environment. To get local weather, you would need to run this code in an environment where geolocation is permitted and provide your own OpenWeatherMap API key.

Inspirational Quote: Displays a random inspirational quote to boost your motivation throughout the day. Quotes are loaded from a local fallback list.

Local Storage: All your mood logs and To-Do list items are saved directly in your browser's LocalStorage, ensuring your data persists across sessions.

🚀 How to Use
Open index.html: Simply open the index.html file in your web browser.

Log Your Mood: Click the "Log Mood" button in the Mood Log card. Select an emoji that represents your current feeling and click "Save Mood".

Manage To-Dos: Type a task into the input field in the To-Do List card and click "Add" or press Enter.

Check the box next to a task to mark it as completed.

Click the trash can icon to delete a task.

Use the Pomodoro Timer:

Click "Start" to begin a 25-minute work session.

Click "Pause" to temporarily stop the timer.

Click "Reset" to restart the timer for the current mode.

Toggle between "Work" and "Break" modes using the buttons above the timer.

View Weather & Quote: The Weather and Quote of the Day cards will automatically display information upon loading the dashboard.

🛠️ Development Setup
This project is a single-page application and does not require any complex build steps.

Clone the repository (if applicable):

git clone <repository-url>
cd life-compass-dashboard

Open index.html: You can directly open the index.html file in any modern web browser.

API Keys (Optional for full functionality)
OpenWeatherMap API Key:

To enable live weather data based on your location (if running in a permissive environment), you'll need an API key from OpenWeatherMap.

Once you have the key, replace 'YOUR_OPENWEATHER_API_KEY' in the JavaScript section of index.html with your actual key.

📂 Project Structure
.
├── index.html          # Main dashboard HTML structure, CSS, and JavaScript
└── README.md           # This file

📜 Technologies Used
HTML5: For the core structure of the dashboard.

CSS3: Custom styles for layout and aesthetics.

Tailwind CSS: A utility-first CSS framework for rapid UI development and responsive design.

JavaScript (ES6+): For all interactive elements, LocalStorage management, and API integrations.

Font Awesome: For various icons used throughout the dashboard.

✨ Future Enhancements
User authentication for multi-device data synchronization.

More advanced task management features (e.g., due dates, priorities).

Customizable Pomodoro timer durations.

Integration with other APIs (e.g., news headlines, calendar events).

Theming options (light/dark mode).
