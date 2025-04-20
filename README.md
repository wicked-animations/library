# 🔥 Wicked Animations

A utility-first CSS animation library for creating slick UI with minimal effort.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm version](https://img.shields.io/badge/npm-1.0.0-blue.svg)](https://www.npmjs.com/package/wicked-animations)

## ✨ Features

- **Utility-First Approach**: Apply animations with simple class names
- **Lightweight**: Only include what you need
- **Customizable**: Adjust timing, delays, and more
- **No Dependencies**: Pure CSS/SCSS solution
- **Modern Animations**: Fade, slide, bounce, flip, rotate, and more

## 📦 Installation

```bash
npm install wicked-animations
# or
yarn add wicked-animations
```

Or include it directly in your HTML:

```html
<link rel="stylesheet" href="https://unpkg.com/wicked-animations@1.0.0/dist/wicked.css">
```

### Import in JavaScript

If you're using a module bundler (webpack, Parcel, Vite, etc.), you can import the CSS directly in your JavaScript file:

```javascript
// In your main JavaScript file
import 'wicked-animations/dist/wicked.css';
```

### Import in SCSS/Sass

If you're using SCSS/Sass:

```scss
// In your main .scss file
@import 'wicked-animations/dist/wicked.css';
```

## 🚀 Quick Start

Simply add the appropriate class to any element you want to animate:

```html
<div class="wicked-fadeIn">I'll fade in!</div>
<div class="wicked-bounce">I'll bounce!</div>
<div class="wicked-slideInLeft">I'll slide in from the left!</div>
```

## ⏱️ Timing & Delays

Customize animation duration and delays:

```html
<!-- Duration options: 300ms, 500ms (default), 700ms -->
<div class="wicked-fadeIn duration-700">Slower fade in</div>

<!-- Delay options: 100ms, 200ms, 300ms -->
<div class="wicked-fadeIn delay-200">Delayed fade in</div>
```

## 🎭 Available Animations

Wicked Animations includes a wide variety of animation effects:

### Fade Animations
- `wicked-fadeIn`, `wicked-fadeOut`
- `wicked-fadeInTop`, `wicked-fadeOutTop`
- `wicked-fadeInBottom`, `wicked-fadeOutBottom`
- `wicked-fadeInLeft`, `wicked-fadeOutLeft`
- `wicked-fadeInRight`, `wicked-fadeOutRight`

### Slide Animations
- `wicked-slideInTop`, `wicked-slideOutTop`
- `wicked-slideInBottom`, `wicked-slideOutBottom`
- `wicked-slideInLeft`, `wicked-slideOutLeft`
- `wicked-slideInRight`, `wicked-slideOutRight`

### Bounce Animations
- `wicked-bounce`
- `wicked-bounceInTop`, `wicked-bounceOutTop`
- `wicked-bounceInBottom`, `wicked-bounceOutBottom`
- `wicked-bounceInLeft`, `wicked-bounceOutLeft`
- `wicked-bounceInRight`, `wicked-bounceOutRight`

### And many more...
- Flip animations
- Rotate animations
- Scale animations
- Special effects (pulse, shake, wave, etc.)

## 📄 License

Wicked Animations is [MIT licensed](LICENSE).

---