📘 Wikipedia Search Application

A simple and responsive web application that allows users to search Wikipedia articles in real time. The app fetches results from the Wikipedia API and displays the title, description, and direct links to relevant articles.
A responsive web app that fetches real-time Wikipedia search results using JavaScript and Fetch API. Built with HTML, CSS, and Bootstrap for a clean and user-friendly UI.

🚀 Features:
 Live Wikipedia article search.
 Displays article titles, short descriptions, and clickable links.
 Responsive user interface.
 Loading spinner while fetching data.
 Clean and user-friendly design.
 
🛠️ Technologies Used:
  HTML5
  CSS3
  JavaScript (DOM Manipulation & Fetch API)
  Bootstrap
 
⚙️ Functionality:
   Users can enter a keyword in the search input box.
   On clicking the search button (or pressing Enter), the app sends a request to the Wikipedia public API.
   A loading spinner appears while data is being fetched.
 
 The app dynamically displays:
   Article title.
   Short description.
   A clickable link to the full Wikipedia page.
   Results are updated in real time without refreshing the page.
   If no results are found, a user-friendly message is displayed.

🧠 How It Works (Behind the Scenes):
   Captures user input using JavaScript DOM methods.
   Uses the Fetch API to call Wikipedia’s search endpoint.
   Parses the JSON response.
   Dynamically creates and appends result elements to the page.
