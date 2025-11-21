# bropr 

A minimalist, terminal-aesthetic web browser built from scratch in Rust.  
This is a **vibe-driven project** about the joy of building, learning, and understanding the web's core technologies.  

---

## 📺 Screen  

bropr runs in a **native GUI window** styled to feel like a classic terminal.  
- Dedicated URL bar  
- Scrollable content area  
- Retro dark theme with a monospaced font  

---

## ✨ Features  

- **Terminal-Styled GUI** – Native graphical window with retro vibes and monospaced font.  
- **Dual-Mode Navigation** – Input bar supports direct URLs and search queries (via DuckDuckGo).  
- **Clickable Hyperlinks** – `<a>` tags are identified and rendered as clickable buttons.  
- **Asynchronous by Design** – Powered by Tokio, ensuring the UI never freezes during page loads.  
- **Core Browser Logic** – Fetches, parses, and renders webpage text while ignoring scripts and syles.  

---

## 📂 Project Structure  

bropr/

├── src/

│ └── main.rs # Core application logic

├── assets/

│ └── Hack-Regular.ttf # Required font file

├── Cargo.toml # Project manifest and dependencies

└── README.md # You are here!


---

\



