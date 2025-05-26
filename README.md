Leetcode Metrics App (JS)
A web app that fetches and visualizes Leetcode user progress stats (Easy, Medium, Hard problems solved) using JavaScript, HTML, CSS, and the Leetcode GraphQL API.

Features
Search Leetcode username to view problem-solving stats
Displays progress circles for Easy, Medium, and Hard difficulty levels
Shows submission statistics for each difficulty level
Responsive and clean UI

How to Use
Open the app in your browser
Enter your Leetcode username in the input field
Click Search
View your progress stats on the page

Technologies Used
HTML
CSS
JavaScript (Vanilla)

Leetcode GraphQL API (via a CORS proxy)
***IF NOT ABLE TO FIX PROXY 
VISIT = https://cors-anywhere.herokuapp.com/corsdemo AND ALLOW TEMPORARY ACCESS TO YOUR USERNAME 

How to Run Locally
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
Open index.html in your favorite browser
Make sure you have internet connection for the API requests

Notes
This project uses a CORS proxy to bypass Cross-Origin issues when fetching data from Leetcode API.
The app requires a valid Leetcode username to fetch stats.
Sometimes, the proxy service may be slow or unavailable.

Future Improvements
Add error handling for invalid usernames or network failures
Improve UI/UX and make it mobile-friendly
Cache API responses for faster repeated searches

Author
Your Name — RajaNamdeo13
