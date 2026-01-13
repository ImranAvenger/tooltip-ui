# 🎯 Tooltip UI

A clean and simple tooltip component created with **HTML and CSS only** – no JavaScript required!

![Tooltip Demo](https://img.shields.io/badge/HTML5-CSS3-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📋 About This Project

This project demonstrates how to create an interactive tooltip that appears above elements when hovering, using only HTML and CSS. It's a great beginner-friendly project to master:

- ✅ CSS Positioning
- ✅ Hover Effects (`:hover` pseudo-class)
- ✅ CSS Pseudo-elements (`::before` and `::after`)
- ✅ CSS Transitions and Animations
- ✅ Creating visually appealing UI without JavaScript

---

## 🎨 Features

- **Pure CSS**: No JavaScript dependencies
- **Smooth Animations**: Fade-in effect with transitions
- **Responsive Design**: Works on all screen sizes
- **Arrow Pointer**: Small triangle connecting tooltip to element
- **Beginner-Friendly**: Simple, well-commented code

---

## 📁 Project Structure

```
tooltip-ui/
├── index.html      # HTML structure with button and tooltip
├── style.css       # All styling and animations
├── README.md       # Project documentation
└── LICENSE         # MIT License
```

---

## 🚀 How to Use

1. **Download or Clone** this repository
2. **Open `index.html`** in your browser
3. **Hover over the button** to see the tooltip appear

### Using in Your Project

To create a tooltip element, add the `tooltip-wrapper` class with a `data-tooltip` attribute:

```html
<button class="tooltip-wrapper" data-tooltip="Your tooltip text here">
  Hover over me
</button>
```

---

## 💡 How It Works

### HTML
The `data-tooltip` attribute stores the tooltip text:
```html
<button class="tooltip-wrapper" data-tooltip="I'm a CSS tooltip!">
  Hover over me
</button>
```

### CSS
The tooltip is created using CSS pseudo-elements:

- **`::before`**: Creates the tooltip text box
- **`::after`**: Creates the arrow/triangle pointer

When you hover, both elements become visible through the `:hover` pseudo-class.

---

## 🎓 Learning Points

### Key CSS Concepts Used

| Concept | Purpose |
|---------|---------|
| `position: absolute` | Position tooltip relative to button |
| `::before` & `::after` | Create tooltip box and arrow |
| `:hover` | Show tooltip on mouse hover |
| `transform` | Center elements perfectly |
| `opacity` & `visibility` | Hide/show tooltip smoothly |
| `content: attr()` | Get text from HTML attribute |

---

## 📝 Customization

You can easily customize the tooltip by editing `style.css`:

- **Colors**: Change `background-color` values
- **Size**: Adjust `padding`, `font-size`, `border` properties
- **Position**: Modify `bottom`, `left` values
- **Animation**: Change `opacity` and `visibility` transitions

Example: Change tooltip background color
```css
.tooltip-wrapper::before {
  background-color: #ff5722; /* Orange instead of black */
}
```

---

## 🏆 Bonus Features

To enhance this project, you can add:

- ✨ Different animations (fade-in, slide-in, scale-in)
- 🎨 Multiple tooltip positions (left, right, bottom)
- ⌨️ Keyboard accessibility
- 📱 Touch events for mobile devices

---

## 🔗 Resources

- [CSS Positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- [CSS Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
- [CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions)
- [Project on roadmap.sh](https://roadmap.sh/projects/tooltip-ui)

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Feel free to fork this project, make improvements, and submit pull requests!

---

## 👨‍💻 Author

Created as a learning project from [roadmap.sh](https://roadmap.sh/)

Happy coding! 🚀 
