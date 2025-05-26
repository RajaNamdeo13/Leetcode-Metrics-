# Leetcode Metrics App (JS)

A web app that fetches and visualizes Leetcode user progress stats (Easy, Medium, Hard problems solved) using JavaScript, HTML, CSS, and the Leetcode GraphQL API.

---
## Features

- Search Leetcode username to view problem-solving stats
- Displays progress circles for Easy, Medium, and Hard difficulty levels
- Shows submission statistics for each difficulty level
- Responsive and clean UI

---
## How to Use

1. Open the app in your browser  
2. Enter your Leetcode username in the input field  
3. Click **Search**  
4. View your progress stats on the page

---
## Demo

Here is a screenshot of the app showing Leetcode stats for my username:

![Leetcode Metrics Screenshot]("Project Visual/Project screenshot.png")



## Technologies Used

- HTML  
- CSS  
- JavaScript (Vanilla)  
- Leetcode GraphQL API (via a CORS proxy)

> **Note:** If the proxy does not work, visit [https://cors-anywhere.herokuapp.com/corsdemo](https://cors-anywhere.herokuapp.com/corsdemo) and allow temporary access to your username.

---

## How to Run Locally

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. Open `index.html` in your favorite browser  
3. Make sure you have an internet connection for the API requests

---

## Notes

- This project uses a CORS proxy to bypass Cross-Origin issues when fetching data from Leetcode API.  
- The app requires a valid Leetcode username to fetch stats.  
- Sometimes, the proxy service may be slow or unavailable.

---

## Future Improvements

- Add error handling for invalid usernames or network failures  
- Improve UI/UX and make it mobile-friendly  
- Cache API responses for faster repeated searches

---

## Author

Raja Namdeo — [GitHub Profile](https://github.com/RajaNamdeo13)
