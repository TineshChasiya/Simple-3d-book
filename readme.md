# 📘 3D Book Page Flip (HTML & CSS)

A realistic **3D book page flip animation** built using **pure HTML and CSS**.
This project simulates a real book where pages flip in 3D space, just like a physical book.

---

## ✨ Features

* 📖 Realistic **3D page flip effect**
* 🎭 Front & back page support
* 📚 Multi-page book structure
* 🧠 Uses CSS **3D transforms & perspective**
* 🪶 Lightweight (No JS / No library)
* 🎨 Clean, minimal UI

---

## 🛠️ Technologies Used

* **HTML5** – Page & book structure
* **CSS3** – 3D animation & styling

  * `perspective`
  * `transform: rotateY()`
  * `transform-style: preserve-3d`
  * `backface-visibility`
  * `transition`

---

## 📂 Project Structure

```
3d-book/
│
├── index.html
├── style.css
└── README.md
```

---

## 🧠 How It Works

* The **book container** creates a 3D scene using CSS perspective
* Each **page** is stacked using absolute positioning
* Pages flip from the **left side**, like a real book
* The back side of each page is pre-rotated by 180°
* Book depth is created using shadows and pseudo-elements

---

## 📌 Important Design Rules

* Perspective is applied only to the book container
* Rotation is applied only to the page element
* Front and back sides never rotate independently
* Pages overlap using stacking (z-index logic)
* Simple background is used to enhance depth

---

---

## 🚀 Future Enhancements

* Click-based page navigation
* Unlimited pages using JavaScript
* Dynamic book thickness effect
* Mobile touch support
* Dark mode version

---

## 📄 License

This project is free to use for **learning and portfolio purposes**.

---

## 🙌 Author

Tinesh Chasiya
HTML • CSS
