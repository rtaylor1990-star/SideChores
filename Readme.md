# 🌟 SideChores - Daily Chore & Tech-Time Reward Tracker

A fun, kid-friendly mobile & tablet web application designed to help children track daily tasks, earn tech-time rewards, and request screen time redemptions—with a secure Parent Admin dashboard for management.

---

## ✨ Features

- **Child-Friendly Interface**: High-contrast buttons, playful fonts, visual progress indicators, synthesized sound effects, and celebration animations upon task completion.
- **Multi-Child Profiles**: Track individual balances, chore progress, and redemption requests for multiple children.
- **Parent Admin View**: Protected by a 4-digit PIN (Default: `1234`).
  - Add, edit, assign, or delete tasks.
  - Approve or deny tech-time redemption requests.
  - Manually adjust tech-time balances (+/- minutes).
  - Reset daily task completion without losing task definitions.
  - Manage child profiles (add/edit avatars and names).
  - Change the security PIN.
- **Zero Backend Required**: Runs 100% client-side in any web browser and saves all data locally via `localStorage`.

---

## 🚀 Live Demo & Deployment

This project is built as a single-file application (`index.html`), making it instant to host on **GitHub Pages**:

1. Upload `index.html` to your GitHub repository.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, set the Branch to `main` (or `master`) and folder to `/ (root)`.
4. Click **Save**. GitHub will provide your live website URL within a minute.

---

## 🛠️ Built With

- **HTML5 & Vanilla JavaScript** (ES6+)
- **Tailwind CSS** (via CDN for styling)
- **Web Audio API** (for built-in sound effects)
- **Canvas-Confetti** (for completion celebrations)
- **Browser LocalStorage API** (for offline data persistence)

---

## ⚙️ Initial Setup & Security

- **Default PIN**: `1234`
- To change the PIN: Open **Parent Admin** mode using the top-right button, enter `1234`, and navigate to **Security Settings** to set a new 4-digit code.

---

## 📄 License

This project is open-source and free to use under the MIT License.
