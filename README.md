# 🔥 Wicked Animations

A utility-first CSS animation library for creating slick UI & presentation transitions with minimal effort.

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

## 🔄 Animation Sequences

Chain multiple animations together with animation sequences:

```html
<!-- Basic sequence container -->
<div class="sequence-container sequence-gap-medium">
  <!-- Each child will animate one after another -->
  <div class="wicked-fadeIn">First item</div>
  <div class="wicked-slideInRight">Second item</div>
  <div class="wicked-bounce">Third item</div>
</div>

<!-- Add sequence-play class to start the sequence -->
<button onclick="document.querySelector('.sequence-container').classList.add('sequence-play')">
  Play Sequence
</button>
```

### Sequence Options

- **Timing**: `sequence-fast`, `sequence-normal`, `sequence-slow`
- **Gaps**: `sequence-gap-small`, `sequence-gap-medium`, `sequence-gap-large`
- **Auto-play**: Add `sequence-autoplay` to play on page load
- **Custom delays**: `sequence-delay-100`, `sequence-delay-300`, etc.
- **Staggered effects**: `sequence-staggered` for varied animations

## 📄 License

Wicked Animations is [MIT licensed](LICENSE).

---