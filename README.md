# Coding Club — Department & Campus Technical Club Web Portal

An interactive web portal and student engagement platform for the College Coding Club. The platform provides event schedules, technical learning tracks, hackathon registrations, faculty and executive team directories, student authentication, and interactive coding knowledge assessments.

---

## 💻 Portal Sections & Modules

- **Home & Vision**: Highlighting club mission, goals, technical achievements, and executive committee members (`first_page.html`, `front.html`).
- **Learning Tracks**:
  - **Machine Learning**: Deep learning, neural networks, and AI resources (`ml.html`).
  - **Programming Languages**: Foundational and systems programming tracks (`pl.html`).
  - **Open Source**: Git workflows and collaborative development (`openso.html`).
- **Events & Hackathons**: Upcoming club meetups, technical bootcamps, and hackathon registration portals (`event.html`, `hackathon.css`).
- **Student Assessment & Quiz**: Built-in MCQ testing engine for club entry evaluations and weekly knowledge challenges (`Login page/`).
- **Faculty & Leadership**: Detailed profiles of faculty coordinators and student leads (`faultydetail.html`).
- **Inter-Club Synergy**: Exploration and connectivity with partner campus technical societies (`other clubs/`).

---

## 🎨 Design & Technologies

- **Structure**: Semantic HTML5 with dynamic audio/video media support (`backg.mp4`).
- **Styling**: Vanilla CSS3 with fluid responsive layout, custom animations (`ani.css`), custom navigation bars (`navigation.css`), and sleek modern dark/gradient themes (`hackathon.css`, `style.css`).
- **Logic**: Vanilla JavaScript for dynamic DOM updates, authentication validation, and quiz scoring.

---

## 🚀 How to Run Locally

No external framework or compiler is required. 

1. Clone the repository:
   ```bash
   git clone https://github.com/Kabhilan-VS-05/Coding-Club.git
   cd Coding-Club
   ```
2. Open `index.html` (or `first_page.html`) directly in any web browser, or serve with VS Code **Live Server** / Python HTTP server:
   ```bash
   python -m http.server 3000
   ```
3. Visit `http://localhost:3000` to browse the portal.

---

## 📄 License
Developed for university technical activities by [Kabhilan VS](https://github.com/Kabhilan-VS-05).
