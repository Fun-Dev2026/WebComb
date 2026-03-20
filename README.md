# WebComb

WebComb is a premium, high-performance static website designed for modern digital agencies. It features a zero-build architecture, a glassmorphic UI, and seamless page transitions.

## 🚀 Key Features

- **Zero-Build Architecture**: Uses standard HTML5, Vanilla JavaScript, and Tailwind CSS (via CDN) for instant deployment.
- **Dynamic Theming**: Interactive Light/Dark mode with persistence across pages via `localStorage`.
- **Premium Animations**:
  - **Interactive Waves**: A subtle, Perlin noise-based wave overlay that responds to mouse movement and touch interaction.
  - **Text Scramble**: A smooth, looping decoding animation for service descriptions.
  - **Swipe Transitions**: High-fidelity page "wipes" that provide an app-like navigation feel.
- **Glassmorphic Design**: Modern, translucent UI elements with blur effects that adapt dynamically to the selected theme.
- **Interactive Contact Form**: Integrated with **EmailJS** for serverless email dispatch directly from the browser.
- **Mobile Responsive**: Fully optimized for all device sizes from handheld to ultra-wide desktop.

## 🛠️ Tech Stack

- **Structure**: HTML5 Semantic Markup
- **Styling**: [Tailwind CSS](https://tailwindcss.com) (v3.x via CDN)
- **Icons**: [Lucide Icons](https://lucide.dev)
- **Animation**: Custom GSAP-inspired `requestAnimationFrame` logic
- **Email Delivery**: [EmailJS](https://www.emailjs.com)

## 📦 Setup & Deployment

1. **Clone the Repository**:
   ```bash
   git clone <your-repo-url>
   cd WebComb
   ```

2. **Configuration (EmailJS)**:
   - Create a free account at [EmailJS](https://www.emailjs.com).
   - Create two templates: one for the user confirmation and one for the team alert.
   - Replace the `publicKey`, `serviceID`, and `templateID` in the `<script>` block of `contact.html`.

3. **Launch**:
   - Simply open `index.html` in any modern web browser or use a live server extension.

## 🛡️ Security

- All form inputs are sanitized to prevent XSS attacks.
- External links use `rel="noopener noreferrer"` for protection against tabnabbing.
- Responsive scaling ensures UI stability across viewport transitions.

## 📩 Conatct US
- email: contact@webcomb.net

---
Built with AI-assisted workflows and 21st.dev components.
---
Built with precision by WebComb. All rights reserved &copy; 2026.
