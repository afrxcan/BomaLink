# Boma Link – Digital Visitor Management System

This project is a minimalist, secure solution designed to modernize entry protocols for residential estates in Kenya by replacing traditional paper logbooks with a streamlined digital "handshake".


### The challenge

The objective was to build a responsive system that facilitates secure estate access while adhering to the **Kenya Data Protection Act**. Key requirements included:

* Generating time-bound QR access codes for guests.
* Creating a dedicated portal for security personnel to scan and verify entries instantly.
* Ensuring the interface remains minimalist and functional across various devices.

### Links

* Live Site URL: [Coming Soon]

## Our process

### Built with

* Semantic HTML5
* CSS Custom Properties for theme management
* Flexbox and CSS Grid for responsive design
* Mobile-first workflow

### What we learned

* **Glassmorphism:** We implemented a modern "blurred" navigation pane using `backdrop-filter: blur(12px)` to ensure the UI feels premium and stays legible over scrolling content.
* **Design Systems:** We utilized a centralized color palette **Royal Purple (`#6D28D9`)** to maintain consistency across the Resident and Security portals.
* **Hardware Calibration:** We refined our media queries to optimize performance for the management view for both mobile and desktop views.

```css
.navbar {
    background-color: rgba(255, 255, 255, 0.85);
    backdrop-filter: blur(12px);
    position: sticky;
    top: 0;
    z-index: 100;
}

```

### Continued development

Our next steps involve migrating from simulations to a full-stack architecture and integrating live SMS/WhatsApp APIs for real-time visitor alerts and QR code generation and scanning

### AI assistance

Throughout the development and documentation process we usedd **Google Gemini** and **GitHub Copilot** for code suggestions, styling guidance, and README composition. Their assistance helped streamline tasks and maintain consistency across the project.

### Useful resources

* [Mozilla Web Docs: Backdrop Filter](https://www.google.com/search?q=https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter) – Provided the logic for our glassmorphism implementation.

## Author

This project was completed by group **Arsenal**:

* Ernest Gitonga
* Billton Yusuf
* Elijah Mumo

---