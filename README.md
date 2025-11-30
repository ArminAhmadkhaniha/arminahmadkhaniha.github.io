# Armin Ahmadkhaniha - Academic Website

[![Built with Hugo](https://img.shields.io/badge/Built%20with-Hugo-blueviolet?style=flat-square&logo=hugo)](https://gohugo.io/)
[![Theme Blowfish](https://img.shields.io/badge/Theme-Blowfish-3b82f6?style=flat-square)](https://blowfish.page/)

This repository contains the source code for my personal academic website and portfolio. It serves as a central hub for my research in **Quantum Software**, **Quantum Machine Learning**, and **Post-Quantum Cryptography**.

🔗 **Live Site:** [https://arminahmadkhaniha.github.io](https://arminahmadkhaniha.github.io)

## 🛠 Tech Stack

* **Framework:** [Hugo](https://gohugo.io) (Static Site Generator)
* **Theme:** [Blowfish](https://blowfish.page) (Tailwind CSS based)
* **Hosting:** GitHub Pages
* **Deployment:** GitHub Actions (Automated CI/CD)

## 🚀 Running Locally

If you want to run this website on your local machine to test changes:

1.  **Clone the repository** (use `--recursive` to include the theme):
    ```bash
    git clone --recursive [https://github.com/ArminAhmadkhaniha/arminahmadkhaniha.github.io.git](https://github.com/ArminAhmadkhaniha/arminahmadkhaniha.github.io.git)
    cd arminahmadkhaniha.github.io
    ```

2.  **Start the local server**:
    ```bash
    hugo server
    ```

3.  Open your browser to `http://localhost:1313`.

## 📝 Managing Content

### Updating the CV
Edit the markdown file located at:
`content/about/cv/index.md`

### Adding a New Project
Create a new folder and markdown file in the projects directory:
```bash
hugo new content/projects/project-name/index.md