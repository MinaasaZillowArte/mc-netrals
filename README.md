<div align="center">

  <h1 style="font-family: 'Press Start 2P', cursive; text-shadow: 3px 3px 0px #ff00ff;">
    NTRL Community Website
  </h1>

  <p>
    The official web portal for the <b>NTRL Minecraft Community</b>. A retro-themed, dynamic, and responsive website built to serve our players with all the information they need.
  </p>

  <p>
    <img src="https://img.shields.io/badge/status-live-green?style=for-the-badge" alt="Status Live">
    <img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge" alt="License MIT">
    <img src="https://img.shields.io/badge/built%20with-love%20%26%20code-ff00ff?style=for-the-badge" alt="Built with Love & Code">
  </p>

</div>

---

### **<g-emoji class="g-emoji" alias="link" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f517.png">🔗</g-emoji> Live Demo**

> Experience the website live on GitHub Pages:
> **[https://minaasazillowarte.github.io/mc-netrals/](https://minaasazillowarte.github.io/mc-netrals/)**

---

### **<g-emoji class="g-emoji" alias="camera_flash" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4f8.png">📸</g-emoji> Project Showcase**

The NTRL website is designed with a unique retro-futuristic, pixel-art aesthetic.

| Home Page | FAQ Page |
| :---: | :---: |
| _The main landing page invites new players and sets the retro tone._ | _A fully searchable FAQ page with a support chatbot._ |
| ![Home Page Screenshot](https://i.ibb.co/wZjd74hw/image.png) | ![FAQ Page Screenshot](https://i.ibb.co/LdghZcky/image.png) |

| Changelogs | Admin Info |
| :---: | :---: |
| _A dynamic changelog page loaded from a simple JSON file._ | _Meet the team behind the server._ |
| ![Changelog Screenshot](https://i.ibb.co/hx7xvSMv/image.png) | ![Admin Info Screenshot](https://i.ibb.co/B20jx7HD/image.png) |

---

### **<g-emoji class="g-emoji" alias="sparkles" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2728.png">✨</g-emoji> Core Features**

This isn't just a static site. It's packed with features to make it a true community hub.

* **<g-emoji class="g-emoji" alias="art" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3a8.png">🎨</g-emoji> Unique Retro-Futuristic UI:**
    * Styled with the classic "Press Start 2P" pixel font.
    * A vibrant color palette of cyan (`#00f6ff`) and magenta (`#ff00ff`) on a dark background.
    * "Pixel-shadow" effects on cards and buttons for a chunky, 8-bit feel.
    * Subtle background animations and scroll-triggered fade-in effects for a dynamic experience.

* **<g-emoji class="g-emoji" alias="floppy_disk" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4be.png">💾</g-emoji> JSON-Powered Dynamic Content:**
    * The **FAQ** and **Changelogs** pages fetch their content from `.json` files (`faq.json`, `changelogs.json`).
    * This allows server admins to update crucial information easily without ever touching the HTML code.

* **<g-emoji class="g-emoji" alias="iphone" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4f1.png">📱</g-emoji> Fully Responsive Design:**
    * A clean mobile-first approach ensures the site is perfectly usable on any device.
    * Includes a sleek, full-screen mobile navigation menu.

* **<g-emoji class="g-emoji" alias="mag" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f50d.png">🔎</g-emoji> Interactive FAQ System:**
    * A live search bar that filters questions in real-time.
    * Questions are presented in an accordion-style layout, keeping the UI clean.
    * Features an integrated **Support Chatbot** that provides instant answers by searching the `faq.json` data for keywords.

* **<g-emoji class="g-emoji" alias="bookmark_tabs" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4d1.png">📑</g-emoji> Versioned Changelog:**
    * Changelogs are clearly organized by version number.
    * Features a scroll-spy navigation sidebar that highlights the current version being viewed.
    * Changes are tagged (`NEW`, `BUG`, `FIXED`, `REMOVED`) with distinct colors for at-a-glance understanding.

* **<g-emoji class="g-emoji" alias="busts_in_silhouette" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f465.png">👥</g-emoji> Community Pages:**
    * **Info Admin:** A dedicated page to introduce the server owners and staff.
    * **Recruitment:** Outlines open staff positions with detailed responsibilities and requirements, linking directly to an application form.

---

### **<g-emoji class="g-emoji" alias="computer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4bb.png">💻</g-emoji> Tech Stack**

This project leverages modern web technologies while maintaining a simple, dependency-free vanilla stack.

* **HTML5**
* **[Tailwind CSS](https://tailwindcss.com/)** - For utility-first styling.
* **Vanilla JavaScript** - For all dynamic functionality, including the FAQ/Changelog loaders and the support bot logic.
* **JSON** - As a lightweight database for site content.

---

### **<g-emoji class="g-emoji" alias="gear" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2699.png">⚙️</g-emoji> Getting Started**

Since this is a vanilla project, running it locally is incredibly simple.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/minaasazillowarte/mc-netrals.git](https://github.com/minaasazillowarte/mc-netrals.git)
    ```
2.  **Navigate to the directory:**
    ```sh
    cd mc-netrals
    ```
3.  **Open `index.html` in your browser:**
    * You can simply double-click the file, or use a local server extension like Live Server in VS Code for a better development experience.

---

### **<g-emoji class="g-emoji" alias="pencil2" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/270f.png">📝</g-emoji> How to Manage Content**

The biggest advantage of this project is the ease of content management.

#### **Updating the FAQ**

To add, remove, or edit a question, simply open and edit the `faq.json` file. The structure is self-explanatory.

```json
{
  "faq": [
    {
      "category": "Pertanyaan Umum",
      "items": [
        {
          "question": "Ini pertanyaan baru saya?",
          "answer": "Ini adalah jawaban untuk pertanyaan baru. Javascript akan otomatis menampilkannya di halaman FAQ.",
          "keywords": ["kata", "kunci", "baru", "untuk", "bot"]
        }
      ]
    }
  ]
}
