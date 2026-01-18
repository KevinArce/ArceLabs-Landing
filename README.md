# Interactive Particle Landing Page 🌌

A next-generation, sci-fi themed landing page featuring a holographic HUD and a dynamic particle text morphing system. Designed for developers, data scientists, and innovators who want to showcase their portfolio with a "wow" factor.

![Preview](screen.png)

## ✨ Features

*   **Particle Text Morphing**: Smoothly transitions between keywords (e.g., your name -> your skills).
*   **Holographic HUD**: Glassmorphism-styled "Heads Up Display" to showcase key stats and links.
*   **Interactive**: Particles scatter and change color on mouse interaction.
*   **Zero Dependencies**: Built with Vanilla JS and Tailwind CSS (via CDN) for instant deployment.
*   **Responsive**: Adaptive layout that works on desktop and mobile.

## 🚀 Quick Start

1.  **Clone the repo** (or fork it!):
    ```bash
    git clone https://github.com/yourusername/interactive-landing-page.git
    ```
2.  **Open `code.html`** in your browser. That's it!

## 🛠️ Customization

### Changing the Morphing Text
Open `code.html` and look for the `texts` array in the `<script>` section (approx line 100):

```javascript
// Configuration
const texts = ["YourName", "Competency", "Skill 1", "Skill 2"];
```

### Updating the HUD Stats
Edit the HTML inside the `<!-- Holographic HUD -->` section. You can simply change the text within the paragraph tags:

```html
<!-- Stat 1 -->
<div>
    <p class="...">Certifications</p>
    <p class="...">5+ Completed</p>
</div>
```

### Adjusting Colors
The project uses Tailwind CSS. You can modify the custom config in the `<head>`:

```javascript
colors: {
    primary: "#3b82f6", // Change this
    "accent-cyan": "#00d4ff", // And this
    // ...
}
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE). Feel free to fork, modify, and use it for your own portfolio!

---

*Created by [Kevin Arce](https://github.com/kevarce)*
