# 🗂️ Base Folio

My personal portfolio website: one place for my work, experience, credentials and writing.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 🎯 Purpose

I wanted a simple, fast site that shows who I am and what I build, without a heavy framework or build step. It's also my starting point for anyone who wants to work with me or follow my work.

## 🧭 What You'll Find

| Page | What's there |
| --- | --- |
| 🏠 **Home** | A quick intro and featured projects |
| 👤 **About** | My background and what drives me |
| 💻 **Projects** | Things I've built, such as ZIPURL, Prichat, Trip Tree and Task Tracker CLI |
| 💼 **Experience** | Where I've worked and what I did there |
| 🏅 **Credentials** | Certifications and courses |
| ✍️ **Blog** | Notes on software, AI and tech ([more on Medium](https://medium.com/@us837)) |

## 🛠️ How I Built It

- **Plain HTML pages**: no framework and no build step. Each page is a standalone `.html` file.
- **Tailwind CSS (CDN)**: all styling uses utility classes, with a dark theme.
- **Lucide icons**: lightweight icons loaded from a CDN.
- **Markdown blog**: posts live in `blogs/` as `.md` files and are rendered in the browser with [marked.js](https://marked.js.org/).

```
base-folio/
├── index.html         # Home
├── about.html
├── projects.html
├── experience.html
├── credentials.html
├── blog.html          # Loads posts from /blogs
├── blogs/             # Markdown blog posts
└── assets/            # Images for the blog and credentials
```

## 🚀 Run It Locally

```bash
git clone https://github.com/us837/base-folio.git
cd base-folio
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

> 💡 Use a local server instead of opening the files directly, because the blog fetches its Markdown posts.

## 🤝 Feel Free To

- ⭐ Use this repo as a template for your own minimal portfolio
- 🐛 Open an issue if something looks broken
- 💬 Connect with me on [LinkedIn](https://www.linkedin.com/in/us837/), [X](https://x.com/ujwal_sharma_ji) or [GitHub](https://github.com/us837)

---

<p align="center">Built by <b>Ujwal Sharma</b></p>
