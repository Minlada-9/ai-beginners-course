# 🤖 AI Academy — Artificial Intelligence Fundamentals Course (AI for Beginners)

This landing page introduces the "AI for Beginners" course, a 6-week introductory artificial intelligence course for beginners. It includes information on course topics, instructors, schedule, tuition packages, FAQs, and a registration form.

🔗 Demo: [https://minlada-9.github.io/ai-beginners-course/](https://minlada-9.github.io/ai-beginners-course/)

---

## ✨ Main Features

- **Navbar** with scrollable menus for each section of the page. And a mobile hamburger menu.
- **Hero Section:** Summary of course highlights.
- **6-Week Course Topics:** From AI basics to the final project.
- **Instructors:** Introduction of each instructor.
- **Schedule:** Specifying the date, time, and learning format (online/classroom) for each week.
- **Tuition Packages:** 3 levels (Beginner/Standard/Premium) with benefits for each package.
- **Frequently Asked Questions (FAQ)** in accordion format (`<details>`).
- **Contact & Registration Form:** Including contact information.

---

## 🛠️ Technologies Used

- **HTML:** — The entire webpage structure is in a single file (`index.html`).
- **Tailwind CSS:** — Used via [Tailwind CDN](https://cdn.tailwindcss.com) for styling. Utility-first with an additional `output.css` file
- **Vanilla JavaScript** — A small script for enabling/disabling the mobile menu

> This project is a purely static landing page. There's no backend, no database, and the contact form isn't yet connected to a real submission system (no actions/JS for submitting yet).

---

## 📁 Project Structure

```
ai-beginners-course/
├── index.html # The entire main webpage (Landing Page)
└── output.css # Additional CSS file (e.g., built-in Tailwind or additional styles)
```

---

## ⚙️ How to Use

This project is a static webpage; no dependencies or builds are required.

### Direct Activation

Open the `index.html` file with your browser.

### Or run it via a local server (recommended)

```bash
npx serve .
```

or

```bash
python3 -m http.server 5500
```

then open your browser to `http://localhost:5500`

---

## 📌 Note

- The "Contact & Enrollment" form is currently just a UI. It does not yet connect to a backend/email/Google Sheet to collect actual data. For real-world use, you need to add an endpoint or form acceptance service (e.g., Formspree, Google Forms, or write your own API).
- Images on the webpage are from Unsplash (credits are indicated in the code comments).

---

## 📄 License

MIT License
