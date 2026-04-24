Create a **simple, modern, and responsive web app** using only **HTML, CSS, and basic JavaScript** that can be hosted on **GitHub Pages**.

---

### 🎨 Design Requirements:

* Main theme color: **#5e17eb** (use for headings, buttons, highlights)
* Clean, minimal UI (no heavy boxes, use simple row layout)
* Proper spacing and modern font
* Fully mobile-friendly

---

### 🧵 App Title Section:

* Centered heading: **"Bhagya Tailor"**
* Tagline below: **"Make you Shine"**
* Use main purple color for styling
* Show Instagram link at top (clickable)

---

### 🧾 Input Section (Row-Based Layout):

Each product should be added in a **single row (not card/box style)**:

Fields in one row:

* Product Description (optional)
* Image Upload (optional)

  * Show preview after upload
* Quantity (Item count)
* Original Price (₹)
* Discount % (optional)
* Final Price (₹)

---

### ⚙️ Logic:

* If **Discount % is entered → auto calculate Final Price**
* If **Final Price is entered → auto calculate Original Price**
* Multiply by quantity for total item cost

---

### 💰 Price Summary:

* Show per item:

  * Original Price
  * Discount %
  * Final Price
* Allow multiple product rows (Add button)

---

### 🧮 Total Section:

* Show:

  * Total Original Price (with strike-through)
  * Total Final Price
  * Total Savings = Original - Final
* If savings < ₹50 → **do not show savings**
* Highlight totals using **#5e17eb**

---

### 📞 Contact Section:

* Show at top and bottom:

  * Instagram:
  * 
* WhatsApp Number:

* Add text: **"Payment via QR Code"**

* QR Image:

* Footer text:

  * "Thank You ❤️"
  * Instagram link again

---

### 📄 Export Feature:

* Add button: **"Download as PDF"**
* Use CDN:

  * html2canvas
  * jsPDF
* Export should include:

  * Product details
  * Image (if uploaded)
  * Pricing
  * Total summary

---

### ➕ Extra Features:

* Button to **Add Multiple Items dynamically**
* Smooth hover effects using **#5e17eb**
* Fast and lightweight (no frameworks)

---

### 📦 Output:

* Provide **single HTML file**
* Include **internal CSS + JavaScript**
* Beginner-friendly and clean code

