Nexus Search ✨

> A sleek, modern, ultra-responsive single-page app for discovering files in open directories using advanced Google search techniques (Google Dorks).






---

🚀 Overview

Nexus Search is a lightweight, zero-dependency, browser-only single-file app (index.html) that helps you construct and launch powerful Google "dork" searches to find publicly accessible open directories and direct file links. The UI is dark-themed, responsive, and designed for fast, effortless searching on any device.

> Important: Nexus Search does not host or provide files. It only helps find publicly-indexed resources via Google. Always respect copyrights and the terms of service of the sites you visit.




---

✨ Features

Modern & Sleek UI — Dark theme built with Tailwind-style utility classes for a buttery-smooth feel.

Fully Responsive — Mobile-first layout that looks great on phones, tablets, and desktops.

File Type Filtering — One-click presets for movies, music, books, images, software, and custom file lists.

Glowing Search Bar + Smooth Interactions — Focus glow, micro-animations, keyboard-friendly UX.

Zero Dependencies — A single index.html file — no build tools, no frameworks, no backend.

Quick Deploy — Host on GitHub Pages, Netlify, Vercel, or any static host.



---

🔧 How it works (in one line)

When you search, Nexus Search builds a Google Dork like:

"The Blacklist S01" +(mkv|mp4|avi) -inurl:(jsp|pl|php|html|aspx) intitle:index.of

That query instructs Google to look for pages containing your search term, with the listed file extensions, with "index of" in the title, while excluding common dynamic page extensions.

Nexus Search opens the generated query in a new tab so you can inspect results and navigate to direct file links in public directories.


---

🧭 Quick Start — Local

1. Clone the repo:



git clone https://github.com/msrofficial/nexus-search.git
cd nexus-search

2. Open index.html in your browser (double-click or open index.html).



That's it — the entire app runs locally in the browser.


---

☁️ Deploy (Vercel / Netlify / GitHub Pages)

1. Fork this repository.


2. Connect your fork to Vercel or Netlify — or enable GitHub Pages from the repo settings.


3. The single-file site will deploy automatically — no build step required.




---

🔎 Usage & Examples

Type your search term (e.g., The Blacklist S01).

Pick a file type preset (Movies, Music, Books, Software, Images) or build a custom extension list.

Use advanced options to exclude filetypes or directories or to add site: restrictions.

Press Enter or click Search — a new tab opens with Google results for the constructed dork.


Example custom query:

"My Favorite Album" +(mp3|flac) -inurl:(php|aspx) intitle:index.of site:example.com


---

🛠️ Customization

Change presets, placeholder text, or UI copy directly inside index.html.

Add new extension groups (comma or pipe separated) for specialized searches.

Styling: tweak the embedded CSS variables for accent color or dark/light theme toggles.



---

⚠️ Disclaimer

This tool is provided for educational and legitimate-surfacing-of-publicly-indexed-content purposes only. The author does not encourage or condone piracy or the unlawful distribution of copyrighted material. Users are solely responsible for the legality of the content they access.


---

🤝 Contributing

Contributions are welcome!

Fork the repo

Create a feature branch

Submit a PR with a clear description


Please keep changes focused, test on mobile, and avoid adding heavy toolchain requirements.


---

📇 Creator

Sakibur Rahman — @msrofficial

Website: msrsakibur.site



---

📜 License

This project is released under the MIT License. See LICENSE for details.


---

Useful Tips

Use quotes to force phrase matching: "Doctor Who S02".

Combine site: to scope results (e.g., site:edu or site:example.com).

If Google blocks requests or shows captchas, try smaller queries or use Google search operators more conservatively.



---

Made with ❤️ by Sakibur Rahman — fork, customize, and share.

