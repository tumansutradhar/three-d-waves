# 3D Waves

An interactive 3D wave animation effect built with pure HTML, CSS, and Tailwind CSS. Features concentric rippling circles with synchronized up-down animations creating a mesmerizing wave pattern.

## About The Project

3D Waves showcases dynamic CSS animations and Tailwind utility classes:
- What it solves: Demonstrates advanced CSS animation techniques and creates visually striking interactive effects
- What makes it unique: Concentric circle design with staggered animations, responsive sizing using Tailwind viewport units (vw), and smooth up-down motion effects
- What was learned: CSS keyframe animations, animation timing/delays, Tailwind CSS custom utilities, responsive design patterns, and creating engaging visual effects

The project uses 24+ nested circles with progressive sizing and custom animation delays to create a hypnotic wave ripple effect on a black background.

## Built With

- HTML5
- CSS3 (keyframe animations, transitions)
- Tailwind CSS 4 (utility classes and custom animations)

## Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, Edge)
- Code editor (optional, for modifications)
- Node.js and npm (optional, if modifying Tailwind config)

### Installation

1. Clone the repo
   ```bash
   git clone https://github.com/tumansutradhar/three-d-waves.git
   cd three-d-waves
   ```

2. Open the site
   ```bash
   # Simply open index.html in your browser
   open index.html
   # Or use a local server for better performance
   python -m http.server 8000
   # Visit http://localhost:8000
   ```

3. View the animation
   - The wave effect plays automatically on load
   - Responsive on all screen sizes

## Usage

The animation is self-contained and runs automatically once the page loads. No user interaction required to see the effect.

**Customization:**
- Adjust animation speed: Modify `animation-duration` in `style.css`
- Change colors: Replace `border-white` with desired Tailwind color
- Alter sizing: Adjust the `w-[Xvw]` and `h-[Xvw]` classes in HTML
- Wave intensity: Change timing functions (e.g., ease-in-out, linear)

Example customization:
```html
<!-- Change border color -->
<div class="border-blue-400"></div>

<!-- Adjust animation speed -->
@keyframes upDown {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-20px); /* increase value for bigger wave */ }
}
```

## Features

- 24 concentric animated circles
- Smooth up-down wave motion with synchronized timing
- Responsive sizing using viewport units (vw)
- Black background with white border circles
- CSS keyframe animations for smooth motion
- Tailwind CSS utility-first styling
- Footer copyright attribution
- Mobile-friendly and responsive
- No JavaScript required (pure CSS animation)
- Customizable animation timing and colors

## Project Structure

```
three-d-waves/
├── index.html           # Main HTML with circles markup
├── assets/
│   ├── style.css       # Compiled Tailwind and custom animations
│   └── favicon.svg
├── LICENSE.md
└── README.md
```

## Roadmap

- [x] Basic wave animation
- [x] Responsive design
- [x] Customizable colors and timing
- [ ] Interactive controls (play/pause)
- [ ] Color theme switcher
- [ ] Multiple animation patterns
- [ ] Sound synchronization
- [ ] Performance optimizations for older browsers

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

## Contact

Tuman Sutradhar

- GitHub: [@tumansutradhar](https://github.com/tumansutradhar)
- Email: connect.tuman@gmail.com
- LinkedIn: [Tuman Sutradhar](https://www.linkedin.com/in/tumansutradhar/)

Project Link: [https://github.com/tumansutradhar/three-d-waves](https://github.com/tumansutradhar/three-d-waves)

## Acknowledgments

- Tailwind CSS framework and documentation
- CSS animation best practices and tutorials
- Web design inspiration and visual effects
