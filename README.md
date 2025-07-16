# Cellular Evolution Game

An interactive, one-page web game simulating cellular automata evolution through 10 progressively challenging levels. Built with HTML5, CSS3 (Tailwind), and vanilla JavaScript, this responsive game invites you to explore emergent patterns and tweak cell behavior in real time.

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://bocaletto-luca.github.io/Evolution/index.html)

---

## 🚀 Features

- 10 curated levels with unique birth/survival rules  
- Responsive HTML5 `<canvas>` animation  
- Real-time controls:  
  - Play/Pause  
  - Single-step tick  
  - Next Level  
  - Speed slider (1–60 FPS)  
  - Click/Tap to toggle cells  
- “Help” overlay explaining rules and controls  
- Automatic level advancement every 20 seconds  
- Fully self-contained—no build tools required  

---

## 🛠️ Technologies

- HTML5 + CSS3 (Tailwind via CDN)  
- JavaScript (ES6, Canvas API)  
- No external dependencies beyond CDN assets  

---

## 📥 Installation & Usage

1. Clone the repository  
   ```bash
   git clone https://github.com/bocaletto-luca/cellular-evolution-game.git
   cd cellular-evolution-game
   ```
2. (Optional) Serve via static server for best performance  
   ```bash
   npx serve .
   ```  
3. Open `index.html` in your browser  
4. Enjoy the game!

> Tip: You can also deploy this page on GitHub Pages, Netlify or any static-site host.

---

## ⚙️ Customization

- **Levels**: Edit `levels.json` to add, remove, or modify levels.  
- **Canvas Dimensions**: Tweak `width`/`height` attributes in `index.html`.  
- **Styling**: Override or extend Tailwind classes in `<style>` or via CDN config.  

---

## 🤝 Contributing

1. Fork the repo  
2. Create a feature branch (`git checkout -b feature/xyz`)  
3. Commit your changes (`git commit -m "Add feature xyz"`)  
4. Push to your fork (`git push origin feature/xyz`)  
5. Open a Pull Request  

Feel free to suggest new levels, UI enhancements, or performance tweaks!

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## ✉️ Contact

Bocaletto Luca  
– GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
– Email: bocaletto.luca@example.com

Enjoy exploring the cellular universe!
