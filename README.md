# Intel: Sustainability Through the Ages

An interactive, visually engaging timeline showcasing Intel's journey through innovation and environmental responsibility, from its founding in 1968 to its ambitious sustainability goals for the future.

![Intel Sustainability Timeline](img/intelbanner.png)

## 🌟 Overview

This project presents a horizontal scrolling timeline that highlights key milestones in Intel's history, with a special focus on sustainability initiatives and technological breakthroughs. The interactive design allows users to explore each milestone in detail through expandable cards.

## ✨ Features

- **Full-Screen Hero Section**: Eye-catching landing page with Intel branding and project introduction
- **Interactive Timeline Cards**: Click to expand cards and reveal detailed information about each milestone
- **Smooth Animations**: Engaging hover effects, transitions, and card flip animations
- **Horizontal Scrolling Design**: Navigate through time with an intuitive left-to-right layout
- **Responsive Design**: Optimized for various screen sizes and devices
- **Accessibility**: Semantic HTML with ARIA labels for improved screen reader support
- **Pure CSS Interactions**: No JavaScript required - all interactions powered by CSS

## 📅 Timeline Highlights

The timeline covers major milestones from 1968 to 2024:

| Year | Milestone | Description |
|------|-----------|-------------|
| **1968** | Intel Founded | Robert Noyce and Gordon Moore establish Intel Corporation |
| **1971** | First Microprocessor | Launch of the 4004, the world's first commercial microprocessor |
| **1978** | 8086 Processor | Introduction of the x86 architecture that powers modern computing |
| **1985** | 386 Processor | 32-bit architecture revolutionizes personal computing |
| **2006** | Peak GHG Emissions | Intel's highest annual greenhouse gas emissions milestone |
| **2020** | RISE Strategy | Launch of Responsible, Inclusive, Sustainable, Enabling strategy |
| **2022** | Net-Zero by 2040 | Commitment to achieve net-zero greenhouse gas emissions |
| **2023** | 99% Renewable Electricity | Achievement of 99% renewable electricity usage worldwide |
| **2024** | Sustainability Summit | First Intel Sustainability Summit uniting industry leaders |

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Advanced styling with:
  - Flexbox and Grid layouts
  - CSS transforms and transitions
  - Custom animations
  - Checkbox-based state management (no JS required)
- **Pure CSS**: All interactions powered by CSS alone

## 📁 File Structure

```
XENSITE/
├── index.html              # Main HTML file with timeline structure
├── style.css               # Complete styling and animations
├── README.md               # Project documentation
└── img/                    # Image assets
    ├── intel-header-logo.svg    # Intel logo
    ├── intelbanner.png          # Hero background image
    ├── ai0.png                  # 1968 - Intel Founded
    ├── ai1.png                  # 1971 - First Microprocessor
    ├── ai2.png                  # 1978 - 8086 Processor
    ├── ai3.png                  # 1985 - 386 Processor
    ├── ai4.png                  # 2006 - Peak GHG Emissions
    ├── ai5.png                  # 2020 - RISE Strategy
    ├── ai7.png                  # 2022 - Net-Zero By 2040
    ├── ai8.png                  # 2023 - Renewable Electricity
    └── ai9.png                  # 2024 - Sustainability Summit
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or build tools required

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/XENSITE.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd XENSITE
   ```

3. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     ```

4. **View the timeline**:
   - Navigate to `http://localhost:8000` (if using a server)
   - Or double-click `index.html` to open directly

## 💡 Usage

1. **Scroll horizontally** through the timeline to view different eras
2. **Click on any card** to expand and reveal detailed information
3. **Click again** (or click another card) to collapse
4. **Hover over cards** to see interactive animations and effects

## 🎨 Customization

### Adding New Timeline Cards

To add a new milestone to the timeline, add the following structure to `index.html`:

```html
<!-- ========== CARD: YEAR ========== -->
<input type="checkbox" id="card-YEAR" class="card-toggle" />
<article class="timeline-card" data-year="YEAR">
  <label for="card-YEAR" class="card-label">
    <img src="img/your-image.png" alt="Your milestone" class="card-image" />
    <span class="card-content">
      <span class="card-year">YEAR</span>
      <span class="card-title">Milestone Title</span>
    </span>
  </label>
  <aside class="card-details">
    <p>
      Detailed description of the milestone...
    </p>
  </aside>
</article>
```

### Styling

All styles are contained in `style.css`. Key sections include:
- **Hero Section**: Full-screen landing page styling
- **Timeline Container**: Horizontal scrolling layout
- **Card Styles**: Individual card appearance and animations
- **Responsive Design**: Media queries for mobile devices

## 🌐 Browser Compatibility

Compatible with modern browsers:
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE11 (limited support)

## 📱 Responsive Design

The timeline is optimized for:
- Desktop (1920px and above)
- Laptop (1024px - 1919px)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## ♿ Accessibility Features

- Semantic HTML5 elements (`<header>`, `<main>`, `<article>`, `<section>`)
- ARIA labels for screen readers
- Keyboard navigation support via checkbox inputs
- High contrast text for readability
- Alt text for all images

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is for educational/demonstration purposes. Please ensure you have appropriate rights to use Intel branding and imagery.

## 👏 Acknowledgments

- Intel Corporation for their commitment to sustainability
- Design inspiration from modern timeline interfaces
- Community feedback and contributions

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

**Made with 💚 to showcase sustainability in tech**
