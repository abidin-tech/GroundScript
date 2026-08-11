 (.gs) — The Ultra-Fast DSL & Engine

> **Write 80% less code. Build web apps, interfaces, and 2D games in minutes, not hours.**

Access the editor here admirable-pothos-e45137.netlify.app
GroundScript is a lightweight, zero-dependency Domain Specific Language (DSL) designed to eliminate boilerplate code. It translates human-readable `.gs` scripts directly into optimized, native HTML and JavaScript with sub-millisecond execution speeds.

---

## 🚀 Why GroundScript?

| Metric | Standard HTML/JS | GroundScript (.gs) |
| :--- | :--- | :--- |
| **Code Length** | ~100 Lines | **~15–20 Lines** ⚡ |
| **Setup Overhead** | NPM, Webpack, Build Tools | **Zero (Runs natively in browser)** |
| **Compilation Speed** | Seconds / Minutes | **< 5 milliseconds** |
| **Learning Curve** | Days to Months | **5 Minutes** |

---

## ⚡ 5-Minute Crash Course

Every `.gs` program is wrapped between `PLAY` and `END`.

### 1. Web & UI Elements
```text
PLAY
  hd "Welcome to GroundScript"       // <h1> Header
  prn "Fast and human-readable text" // <p> Paragraph
  btn "Click Action"                // Styled Button
  
  bx {                              // Box/Card Container
    prn "Card Item"
    btn "Select"
  }
END

2. Variables, Logic & Loops
PLAY
  set score = 100
  
  if (score >= 50) {
    prn "Status: Active"
  }

  // Fast loops using 'rep'
  rep 3 {
    bx { prn "Repeated Element" }
  }
END

3. Game Engine Mechanics (GS GAME MAKER)
GroundScript handles game loops and key inputs without complex event listeners:
PLAY
  set player_x = 100
  set player_y = 100

  // Draw player object
  draw_box player_x player_y

  // Handle Controls
  on_key "ArrowRight" { set player_x = player_x + 5 }
  on_key "ArrowLeft"  { set player_x = player_x - 5 }
  on_key "ArrowUp"    { set player_y = player_y - 5 }
  on_key "ArrowDown"  { set player_y = player_y + 5 }
END

🛠️ How to Run
 * Open index.html in any web browser.
 * Write or paste your .gs code in the editor.
 * See live rendered output instantly.
 * Click Export HTML to output a fully standalone web application.
📜 License
Licensed under the MIT License. Free for personal, open-source, and commercial projects.
Created with passion by Abdeen.
  You can access the editor via this link: admirable-pothos-e45137.netlify.app
احفظ هذا النص داخل ملف باسم **`README.md`** في المجلد الرئيسي لمشروعك، وسيكون الدليل الجاهز والشامل لكل من يزود مشروعك! 🚀⚡

