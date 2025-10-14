# Nexus-Search
Nexus Search
A sleek, modern, and ultra-responsive single-page application for finding files in open directories using advanced Google search techniques. This tool provides a beautiful and intuitive interface to simplify the process of discovering direct download links for various file types.
✨ Features
 * Modern & Sleek UI: A stunning dark-themed interface built with Tailwind CSS for a smooth, butter-like user experience.
 * Fully Responsive: Looks and works great on all devices, from mobile phones to desktops.
 * File Type Filtering: Easily filter your search for specific file types like movies, music, books, or software with a single click.
 * Dynamic & Interactive: Features a glowing search bar on focus, interactive buttons, and smooth transitions.
 * Zero Dependencies: A single index.html file that runs entirely in the browser. No server-side logic, no build process needed.
 * Easy to Deploy: Host it for free on any static site provider like Vercel, Netlify, or GitHub Pages.
🚀 How It Works
Nexus Search doesn't host any files. Instead, it acts as a smart front-end for Google Search. When you search for a term (e.g., "The Blacklist S01"), the application constructs a highly specific search query known as a "Google Dork".
This query looks something like this:
"The Blacklist S01" +(mkv|mp4|avi) -inurl:(jsp|pl|php|html|aspx) intitle:index.of

This query tells Google to find pages that:
 * Contain your search term.
 * Have specific file extensions (like .mkv or .mp4).
 * Have "index of" in the title, which is common for open directories.
 * Exclude common web page extensions to filter out irrelevant results.
The final search is then opened in a new tab, presenting you with a list of publicly accessible directories containing your desired files.
🔧 How to Use & Deploy
This project is incredibly easy to set up.
1. Local Usage:
 * Clone this repository: git clone https://github.com/your-username/nexus-search.git
 * Open the index.html file directly in your web browser.
2. Deployment (Vercel, Netlify, etc.):
 * Fork this repository.
 * Connect your fork to a service like Vercel or Netlify.
 * The project will be deployed automatically. No build configuration is needed!
⚠️ Disclaimer
This tool is provided for educational purposes only. It simplifies access to publicly available information via Google's search engine. Users are solely responsible for the content they access and download. Please respect copyright laws and the terms of service of any website you visit. The creator of this tool does not condone piracy and is not responsible for its misuse.
🧑‍💻 Creator
This project was designed and developed by Sakibur Rahman.
 * GitHub: @msrofficial
 * Website: msrsakibur.site
 * Facebook: [Shondehojonok link shorano hoyeche]
 * Instagram: @msr.sakibur
Feel free to contribute by forking this repository and submitting a pull request!
