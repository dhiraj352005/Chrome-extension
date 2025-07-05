# Chrome-extension
Company : CodeTech IT solutions
name : Dhiraj Raut 
Intern ID:CT04DG142
Domain:React.js Web Development. 
Duration:4 Months 
Mentor:Neela Santhosh Kumar









<img width="828" height="546" alt="Image" src="https://github.com/user-attachments/assets/3df74d2b-0068-4605-8dce-7712ad6777b8" />


Chrome Extension – Personal Productivity Tracker
This Chrome Extension is a personal productivity tracking tool designed to help users stay focused, monitor their time usage, and build better digital habits. The goal behind creating this project was to explore how browser extensions work, improve understanding of background scripts, content scripts, and Chrome APIs, and build something useful for real-world productivity enhancement.

This extension provides an overview of how much time the user spends on websites, tracks visits, and offers basic analytics to give insights into online behavior. It is especially useful for students, developers, remote workers, or anyone who wants to gain better control over their browsing time and habits.

Key Features
Tracks the total time spent on each website (e.g., YouTube, Gmail, LinkedIn)

Stores productivity data locally using Chrome's storage API

Automatically starts tracking when the user opens a tab

Simple popup interface to view productivity summary

Option to reset tracking data anytime

Lightweight and easy to install

Built with plain JavaScript, HTML, and CSS (React/Typescript optional)

Can be enhanced with notifications, reminders, or Pomodoro timers

Why I Built This
As someone who spends a lot of time online for both learning and work, I realized the importance of understanding where my time is actually going. This project helped me learn about the Chrome Extensions API and browser event handling (tabs, windows, storage, etc.), while also building something that solves a practical problem.

Technologies Used
HTML

CSS

JavaScript (Vanilla or optionally React)

Chrome Extensions API (tabs, storage, runtime, alarms)

JSON for manifest configuration

Optionally: Webpack (for bundling if using React)

Folder Structure
arduino
Copy
Edit
productivity-tracker-extension/
├── icons/                     // Extension icon files
├── popup.html                // UI shown when extension is clicked
├── popup.js                  // Logic for popup UI
├── background.js             // Background script to handle tracking
├── content.js                // (Optional) Injected content script
├── styles.css                // Styling for popup
├── manifest.json             // Chrome extension metadata
└── README.md
How It Works
The background script listens for tab changes and tracks how long a tab remains active.

Time is recorded and saved locally using chrome.storage.local.

The popup interface allows users to view how much time they've spent on different domains.

A reset button clears the data and starts fresh.

Tracking continues even if the popup is not opened.

Installation Instructions
Download or clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/productivity-tracker-extension.git
Open Google Chrome and go to:

arduino
Copy
Edit
chrome://extensions/
Enable "Developer mode" (top right corner)

Click on "Load unpacked" and select the root folder of this extension

The extension will appear in your toolbar. Click on it to view your productivity stats.

Ideas for Future Improvements
Add daily, weekly, and monthly reports

Classify websites as "productive" or "distracting"

Add Pomodoro timer integration

Export data as CSV

Sync data using Firebase or local server

Add dark mode for popup interface

Implement user preferences/settings page

Conclusion
This Chrome Extension is a simple but effective productivity tracker built to enhance self-awareness and time management. It combines basic web development skills with browser-specific APIs to create a useful tool for daily use. Whether you're trying to improve your focus or just curious about your browsing habits, this project offers a solid foundation for further development.

Feel free to fork the repository, explore the code, or contribute ideas and improvements.
