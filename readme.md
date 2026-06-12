# Advanced Multi-Mode Mathematical Suite

Created using prompts on Gemini AI. An ambitious, high-performance, and responsive advanced multi-mode calculator dashboard designed for engineers, students, and programmers. Built entirely as a single-file application, it merges classic calculations with advanced analytical tools.

## 🚀 Core Features & Modes

Advanced multi-mode calculator operates across six fully functional mathematical environments:

### 1. Scientific Math Mode
* **Expression Parser:** Powered by **Math.js** to process complex order-of-operations (PEMDAS), nested parenthetical evaluations, and algebraic syntax.
* **Trigonometry & Calculus:** Supports `sin`, `cos`, `tan` (both Radian and Degree calibrations), `log`, `ln`, absolute values, factorial, and powers.
* **Interactive History Log:** Saves calculation logs which can be clicked to instantly recall and inject previous calculations back into the active parser.
* **Memory Registers:** Live `MC`, `MR`, `M+`, and `M-` controls storing values with dedicated HUD status displays.

### 2. Interactive Graphing
* **Dynamic Coordinate System:** A high-performance HTML5 Canvas graphing engine that supports plotting multiple continuous functions like $y = f_1(x)$ and $y = f_2(x)$.
* **Intuitive Viewport Manipulation:**
  * **Pan:** Click and drag anywhere on the canvas to move across the coordinate plane.
  * **Zoom:** Use the mouse scroll wheel or viewport calibration buttons to dynamically rescale coordinates.
* **Floating Live HUD:** Tracks cursor coordinates in real-time ($x, y$) based on current math domains.

### 3. Programmer Suite
* **Multi-Base Synchronizer:** Real-time conversion between Hexadecimal (HEX), Decimal (DEC), Octal (OCT), and Binary (BIN) as you type.
* **Bit Field Visualizer:** Interactive 16-bit register map. Click individual bit slots (Bit 0 to Bit 15) to toggle their state ($0 \leftrightarrow 1$) and watch all bases recalculate instantly.
* **Bitwise Arithmetic:** On-demand operations such as `AND`, `OR`, `XOR`, `NOT`, and bit shifting (`Lsh`, `Rsh`).

### 4. Matrix Studio
* **Dynamic Sizing:** Instantly switches between $2 \times 2$, $3 \times 3$, and $4 \times 4$ matrices.
* **Algebraic Calculations:** Performs matrix addition ($A + B$), subtraction ($A - B$), cross-multiplication ($A \times B$), transposition ($A^T$), determinants ($\det(A)$), and matrix inversion ($A^{-1}$).
* **Accurate Output Formatting:** Fractional and floating-point normalization to safeguard against round-off errors.

### 5. Financial Engine
* **Mortgage / Loan Amortization:** Calculates exact monthly repayment costs, aggregate principal sums, and total interest obligations over long-term durations.
* **Compound Savings Modeler:** Future value calculations for monthly recurring deposits with compound rates.
* **Visual Breakdown Chart:** Highly intuitive dual-color progress bar showing the precise percentage split between principal capital and compound interest payments.

### 6. Universal Unit Converter
* **Diverse Categories:** Supports Length, Mass, Area, Volume, Speed, and Temperature.
* **Real-time Evaluation:** Updates converted dimensions as you type, with an active swap button to reverse target domains.
* **Constant Reference Map:** Generates quick-reference ratios of SI units and physical constants.

---

## 🛠️ Technology Stack & Architecture

* **UI Framework:** Tailwind CSS (fully responsive layout adapting seamlessly from mobile viewports up to widescreen desktops).
* **Parser Engine:** Math.js (provides reliable, bulletproof string parsing and matrix arithmetic).
* **Typography & Icons:** FontAwesome 6 + Google Fonts (Inter & JetBrains Mono).
* **Haptic Audio Feedback:** Custom synthesizer engine leveraging the **Web Audio API** to generate physical mechanical button clicking ticks and tone-differentiated success/error notifications on demand.

---

## ⌨️ Global Keyboard Support

When active in **Scientific Mode**, you can use physical keyboard inputs to streamline operations:

| Key | Action mapped in advanced multi-mode calculator |
| :--- | :--- |
| `0` - `9` | Input Digits |
| `+`, `-`, `*`, `/` | Standard Arithmetic Operators |
| `.` | Decimal Point |
| `(`, `)` | Parenthetical priorities |
| `Backspace` | Delete last input character |
| `Enter` | Run Expression Evaluation (=) |
| `Escape` | Clear active expression (AC) |

---

## 🎨 Creative Custom Themes

Aadvanced multi-mode calculator supports switching themes dynamically from the header bar, altering colors and glowing design accents:

* **Cyberpunk Neon (Default):** High-contrast deep slate with glowing neon blue, violet, and emerald accents.
* **Professional Slate:** High-legibility neutral gray colorway designed for professional mathematical settings.
* **Crimson Sunset:** Dark warm earth tones mixed with vivid rose-gold and copper elements.

---

## 🚀 Running the Application

Because this application relies entirely on client-side compilation and lightweight CDNs, running it is simple:

1. Double-click the `index.html` file or launch it inside a live server.
2. Ensure you have an active internet connection so external libraries (Tailwind CSS, FontAwesome, and Math.js) can compile in real-time.
