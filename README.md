````markdown
# 📚 Book Inventory App

A simple, styled HTML & CSS application to track and visualize book inventory status and ratings. This project demonstrates semantic HTML structure, CSS attribute selectors, and UI organization based on user-defined reading status and personal rating.

## 🔧 Features

- ✅ Semantic HTML table with five columns: **Title**, **Author**, **Category**, **Status**, **Rate**
- ✅ Book entries are categorized as `Read`, `To Read`, or `In Progress`
- ✅ Status and Rating visually represented with styled `<span>` elements
- ✅ Ratings shown using 1–3 dots with gradient fills
- ✅ Pure CSS styling with attribute selectors (no JavaScript)

## 🧩 Technologies Used

- HTML5
- CSS3 (with advanced attribute selectors and gradients)
- No external libraries or frameworks

## 🚀 Getting Started

To run the app locally:

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/book-inventory-app.git
   cd book-inventory-app
```

2. Open `index.html` in your browser:

   ```bash
   open index.html
   ```

No build tools or dependencies required — this is a static project.

## 📁 Project Structure

```
book-inventory-app/
├── index.html        # Main HTML file
└── README.md         # Project description
```

## 🎯 User Stories Fulfilled

* One `<h1>` titled **Book Inventory**
* A `<table>` with five columns: Title, Author, Category, Status, Rate
* Rows classified as `.read`, `.to-read`, or `.in-progress`
* Status and rating are displayed using styled `<span>` elements
* CSS attribute selectors style each book row by status
* Inline ratings (`.rate.one`, `.rate.two`, `.rate.three`) use gradients to reflect user score

## ✨ Screenshots

| Status Types                                              | Rating Example                                               |
| --------------------------------------------------------- | ------------------------------------------------------------ |
| Read, To Read, In Progress rows with gradient backgrounds | 1–3 dot indicators inside `.rate` using background gradients |

## 🧠 Key Learnings

* Use of attribute selectors (`[class="read"]`, `[class^="rate"]`) for fine-grained CSS control
* Inline-block styling for custom UI indicators
* How to visually encode status and rating without JavaScript

## 📝 License

This project is open source and free to use under the [MIT License](LICENSE).
