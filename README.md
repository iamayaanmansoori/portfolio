# Mohd Ayaan Mansoori — Portfolio

Personal portfolio for Mohd Ayaan Mansoori, an Associate Engineer in Infrastructure and Managed Services with a background in Cyber Security and SOC operations.

The site presents professional experience, skills, certifications, and engineering projects in a responsive, single-page layout.

## Features

- Responsive portfolio with dark and light themes
- Professional profile, experience, skills, certifications, and contact sections
- Featured Smart AI-Powered Camera Weapon Detection System project
- Downloadable resume and project imagery
- Optional Gemini-powered SOC Copilot chat and project deep dives
- Contact form that opens a pre-filled email in the visitor's mail application

## Built with

- HTML, CSS, and vanilla JavaScript
- Tailwind CSS via CDN
- Google Fonts
- Google Gemini API (optional AI features)

No build step or package installation is required.

## Contact form email delivery

The Connect form sends submissions to `nolimitayaan@gmail.com` through [FormSubmit](https://formsubmit.co/). The sender's name, email address, subject, and message are processed by FormSubmit to deliver the email.

On the first submission, FormSubmit sends an activation email to the portfolio owner. Open that message and confirm the address; submissions will not be delivered to the inbox until the form is activated. Check spam/junk if the activation email is missing.

## Run locally

Run a static HTTP server from the project directory:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). Alternatively, use the VS Code Live Server extension.

## Optional Gemini configuration

The site works without an API key, but the AI chat and project deep-dive features need a Gemini API key.

1. Copy `config.example.js` to `config.js`.
2. Replace `YOUR_GEMINI_API_KEY_HERE` in `config.js` with your key.
3. Keep `config.js` private. It is excluded from Git by `.gitignore`.

The API key is used by browser-side JavaScript, so it is visible to site visitors. For a public deployment, use a backend proxy rather than publishing a personal API key, and apply appropriate restrictions and quotas to any browser key.

## Deploy

This is a static site and can be hosted on GitHub Pages or another static web host. For GitHub Pages, select the `main` branch and `/ (root)` as the publishing source in the repository's **Settings → Pages**.

## Project structure

```text
.
├── assets/
│   ├── images/
│   └── Mohd_Ayaan_Mansoori_Resume.pdf
├── config.example.js
├── index.html
└── README.md
```

## Featured project

The portfolio highlights a Smart AI-Powered Camera Weapon Detection System using Python, YOLOv8, and OpenCV, with email and Telegram alerts, GPS details, and Hindi/English voice alerts. [View the project repository](https://github.com/iamayaanmansoori/Smart-AI-Powered-Camera-Weapon-Detection-System).

## Contact

- Email: [nolimitayaan@gmail.com](mailto:nolimitayaan@gmail.com)
- GitHub: [iamayaanmansoori](https://github.com/iamayaanmansoori)
