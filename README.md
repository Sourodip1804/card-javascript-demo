# 📺 YouTube Card Generator

A simple JavaScript project that dynamically creates YouTube-style video cards using HTML, CSS, and JavaScript.

The project demonstrates how to generate HTML dynamically with JavaScript template literals and display video information such as title, channel name, views, upload time, duration, and thumbnail.

---

## 🚀 Features

- 📹 Generates YouTube-style video cards dynamically
- 🖼️ Displays video thumbnail
- ⏱️ Shows video duration
- 👤 Displays channel name
- 👀 Automatically formats view counts (e.g., `560K`, `2M`)
- 📅 Displays how many months ago the video was uploaded
- ⚡ Uses JavaScript template literals for dynamic HTML generation

---

## 📂 Project Structure

```
YouTube-Card-Generator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

---

## 📖 How It Works

The project contains a function:

```javascript
createCard(title, cName, views, monthsOld, duration, thumbnail)
```

### Parameters

| Parameter | Description |
|-----------|-------------|
| `title` | Video title |
| `cName` | Channel name |
| `views` | Number of views |
| `monthsOld` | Months since upload |
| `duration` | Video duration |
| `thumbnail` | Thumbnail image URL |

The function:

- Formats the view count into **K** or **M**
- Creates an HTML card using template literals
- Inserts the generated card into the `.container` element

---

## 📸 Example

```javascript
createCard(
    "Video Title here",
    Total Views,
    months,
    "video duration",
    "image link here"
);
```

### Output

- Thumbnail
- Video Duration
- Video Title
- Channel Name
- 560K views
- 7 months ago

---

## 💡 Concepts Practiced

- Functions
- Parameters
- Conditional Statements (`if...else`)
- Template Literals
- String Interpolation
- DOM Manipulation
- `querySelector()`
- `innerHTML`
- Dynamic HTML Generation

---

## 🎯 Learning Objectives

This project helps beginners understand:

- Creating reusable JavaScript functions
- Manipulating the DOM
- Building HTML dynamically
- Working with template literals
- Formatting data for better user experience

---

## ▶️ Getting Started

1. Clone the repository

```bash
git clone https://github.com/your-username/YouTube-Card-Generator.git
```

2. Open the project folder.

3. Open `index.html` in your browser.

That's it! 🎉

---

## 🔮 Future Improvements

- Add multiple cards using an array
- Fetch video data from an API
- Improve responsive design
- Add hover animations
- Display verified channel badges
- Add dark/light mode
- Use `createElement()` instead of `innerHTML`

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project, feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Show Your Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

Happy Coding! 🚀
