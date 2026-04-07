# 🌟 SWE 363 – Assignment 4

> ✨ A responsive **personal portfolio web application** built as part of the SWE 363 Web Development course.  
> 🌗 Featuring a **dark/light theme**, time-based greetings, project filtering and sorting, simple form validation, and modern responsive design.

--- 
## 🌍 Live Link 
### https://lenaashqar.vercel.app/

---

## 📝 Project Description

This project implements a **personal portfolio** website to showcase:
- 🧑 About section
- 🧰 Skills
- 📦 GitHub repositories (via GitHub API)
- 💼 Projects
- ✉️ Contact information
- 🎨 Dynamic theme and UI behavior

### 🌟 Key Functionalities
- Responsive layout supporting mobile, tablet, and desktop.
- Dark/Light theme toggle.
- Time-based greeting (e.g., “Good morning”, “Good evening”).
- Project filtering and sorting.
- Simple frontend-only contact form.
- Clean and structured sections to highlight content effectively.
- Improved performance by further modularizing code.

---

## 🧰 Features

| Feature                   | Description                                                 |
|---------------------------|-------------------------------------------------------------|
| 🌓 Theme Switch           | Dark ↔ Light mode toggle                                     |
| 🕒 Time Greeting          | Displays greeting message based on local time               |
| 🧑 About Section          | Basic introduction and personal info                        |
| 💼 Projects Showcase      | Highlight of personal or academic projects                   |
| 📦 GitHub API Integration | Automatically loads public repositories                                                            |
| 🧰 Skills Section         | Technologies and tools proficiency                          |
| ✉️ Contact Form           | Frontend only (no backend integration)                       |
| 📱 Responsive Design      | Optimized for all screen sizes                              |

---

## 🤖 AI / Assistance Usage

- 🧠 **ChatGPT** for debugging and generating GitHub API section.
- 📄 Detailed usage is documented in [`ai-usage-report.md`](./docs/ai-usage-report.md).

---

## 📂 File Structure

    ```plaintext
    assignment-4/                    ← repository root
    ├─ assignment-4/                 ← application source lives here
    │  ├─ node_modules/              ← installed dependencies
    │  ├─ src/                       ← components, styles, assets, entry files
    │  │  ├─ assets/                 ← images, icons, etc.
    │  │  ├─ components/             ← UI components
    │  │  ├─ App.(jsx)               ← app root component
    │  │  └─ (other app files)       ← configuration or additional folders
    │  ├─ .gitignore
    │  ├─ package.json               ← scripts & dependencies
    │  └─ package-lock.json
    ├─ docs/
    │    ├─ ai-usage-report
    │    └─ technical-report
    ├─ presentation/
    │    ├─ slides.pdf
    │    └─ demo-video.mp4
    ├─ package.json                 ← scripts & dependencies (root)
    ├─ package-lock.json
    └─ README.md



## 🧑‍💻 Setup & Local Run
Follow these steps to run the project locally:

1. Clone the repository  
   ```bash  
   git clone https://github.com/LenaAshqar/assignment-4.git

2. Cd into the project directory
   ```bash  
   cd "/assignment-4"

3. Install npm  
   ```bash  
   npm i

4. Run npm
   ```bash  
   npm run dev    

💡 Once the server starts, open the link provided in your terminal (usually http://localhost:5173
if using Vite).

## 💬 Acknowledgments

🧭 GitDocify
for markdown styling inspiration

🤖 OpenAI (ChatGPT) for development assistance

👩‍🏫 Course instructors and peers for guidance
