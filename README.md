📸 Image Search App

A simple and beautiful Image Search Web Application built using HTML, CSS, and JavaScript, powered by the Unsplash API.
This app allows users to search for any topic and instantly view high-quality images.
It also supports infinite scrolling using a “Show More” button.

✨ Features:
✔ Search for any image using the Unsplash API
✔ Clean and responsive UI
✔ Shows 3 images per row (Desktop)
✔ Mobile and tablet responsive
✔ “Show More” button loads more images (pagination)
✔ Smooth hover effects
✔ Uses modern JavaScript (async/await + fetch API)

🛠️ Tech Stack:

HTML5 – UI structure
CSS3 – Styling & responsiveness
JavaScript (ES6+) – API calls, DOM updates
Unsplash API – Fetching images

🔑 Unsplash API Key
You must generate your own API key from:
👉 https://unsplash.com/developers

Then replace your key in:
const accesskey = "sh8hSpzlRegzd8ZtXANK3NFvrNvKdTt-yizuFP3CM0o";
📂 Project Structure
Image Search App/
│── index.html          # Main application
│── style.css           # Optional external CSS file (if used)
│── script.js           # Optional external JS file (if used)
Since your app uses inline CSS & JS inside index.html, everything is contained in a single file.

🚀 How It Works

User types a search keyword in the input box
JavaScript fetches images from Unsplash API:
https://api.unsplash.com/search/photos?page=${page}&query=${inputData}&client_id=${accesskey}
Results are displayed dynamically as image cards
“Show More” loads more images from next pages
Responsive layout adjusts for mobile/tablet/desktop

📱 Responsive Behavior
Desktops: 3 images per row
Tablets: 2 images per row
Phones: 1 image per row

🔧 How to Run
Just open the index.html file in any browser:
Right-click → Open With → Chrome
