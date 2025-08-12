# Flex Panel Gallery 🎨

An interactive image gallery built with CSS Flexbox and vanilla JavaScript. Click on any panel to expand it and reveal beautiful background images with animated text overlays.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Smooth Animations**: CSS transitions for panel expansion and text reveal
- **Interactive**: Click any panel to expand/collapse
- **Beautiful Imagery**: Uses high-quality Unsplash images as backgrounds
- **Clean Code**: Pure HTML, CSS, and JavaScript - no frameworks needed

## 🚀 Demo

![Flex Panel Gallery Demo](https://user-images.githubusercontent.com/demo.gif)

## 📁 Project Structure

```
05 - Flex Panel Gallery/
├── index-START.html      # Starter template for development
├── index-FINISHED.html   # Complete working version
└── README.md            # This file
```

## 🛠️ How to Use

### Quick Start

1. Open `index-FINISHED.html` in your browser
2. Click on any panel to see the expansion animation
3. Click again to collapse the panel

### Development

1. Open `index-START.html` to begin with the basic structure
2. Follow the JavaScript30 tutorial to implement the functionality
3. Test your changes by opening the file in a browser

## 🎯 Learning Objectives

This project demonstrates:

- **CSS Flexbox**: Advanced flex properties and responsive layouts
- **CSS Transitions**: Creating smooth animations with `transition` property
- **Event Handling**: JavaScript click and transition events
- **DOM Manipulation**: Adding/removing CSS classes dynamically
- **Responsive Design**: Media queries for mobile optimization

## 🎨 Customization

### Change Images

Replace the background URLs in the CSS:

```css
.panel1 {
  background-image: url(YOUR_IMAGE_URL);
}
```

### Modify Text

Update the text content in each panel:

```html
<div class="panel panel1">
  <p>Your</p>
  <p>Custom</p>
  <p>Text</p>
</div>
```

### Adjust Colors

Modify the color scheme in the CSS:

```css
.panel {
  background: #YOUR_COLOR; /* Change panel background */
  color: #YOUR_TEXT_COLOR; /* Change text color */
}
```

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🔧 Technical Details

### CSS Properties Used

- `flex`: Controls panel sizing
- `transition`: Animates property changes
- `transform`: Moves text elements
- `background-size: cover`: Ensures images fill panels

### JavaScript Events

- `click`: Triggers panel expansion
- `transitionend`: Detects when animations complete

## 🤝 Contributing

This is part of the JavaScript30 course. Feel free to fork and customize for your own projects!

## 📚 Resources

- [JavaScript30 Course](https://javascript30.com/)
- [CSS Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
