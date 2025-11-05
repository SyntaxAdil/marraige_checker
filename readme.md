```markdown
# Marriage Eligibility Checker 💍

A fun and interactive web application that checks marriage eligibility either through facial recognition (image upload) or age verification. Built with pure HTML, CSS, and JavaScript.

## 🌟 Features

- **Dual Verification Methods**
  - Image-based verification with scanning animation
  - Age-based verification with input validation

- **Interactive UI**
  - Drag and drop image upload support
  - Real-time scanning animation effects
  - Smooth transitions and hover effects
  - Responsive design for all devices

- **Bilingual Support**
  - Bengali and English mixed interface
  - Culturally relevant messaging

## 🚀 Demo

![Marriage Checker Demo](demo-screenshot.png)

## 📋 Prerequisites

No dependencies required! This is a pure vanilla JavaScript application.

## 💻 Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/marriage-eligibility-checker.git
```

2. Navigate to the project directory
```bash
cd marriage-eligibility-checker
```

3. Open `index.html` in your browser
```bash
open index.html
```

Or simply drag and drop the HTML file into your browser.

## 🎯 Usage

### Method 1: Image Verification
1. Click on "ছবি দিয়ে" (With Image) button
2. Upload your image by:
   - Clicking on the upload area
   - Dragging and dropping an image
3. Wait for the scanning animation (5 seconds)
4. Click "এগিয়ে যান" (Proceed) to see results

### Method 2: Age Verification
1. Click on "বয়স দিয়ে" (With Age) button
2. Enter your age in the input field
3. Press Enter or click the submit button
4. View your eligibility result

## 🎨 Features Breakdown

### Image Upload
- Supports drag and drop functionality
- Visual scanning animation with cyberpunk-style effects
- Preview uploaded image before verification
- Cancel option to re-upload

### Age Verification
- Input validation (age must be between 1-119)
- Real-time button styling based on input
- Enter key support for quick submission
- Error handling with shake animation

### Results Display
- Visual feedback with color-coded results
- Animated scale effects
- Bengali messages for results
- Auto-refresh after 5 seconds

## 📱 Responsive Design

The application is fully responsive and works seamlessly on:
- 📱 Mobile devices (320px and up)
- 💻 Tablets (768px and up)
- 🖥️ Desktops (1024px and up)

### Breakpoints
- **Mobile**: < 480px
- **Tablet**: 481px - 768px
- **Desktop**: > 768px

## 🎭 Customization

### Colors
Primary colors can be modified in the CSS:
```css
--primary-gradient: linear-gradient(135deg, #06b6d4, #3b82f6);
--success-color: #86efac;
--error-color: #fca5a5;
```

### Animation Duration
Adjust timing in the JavaScript:
```javascript
setTimeout(() => {
  // Your code
}, 5000); // Change duration here
```

## 🔧 Technical Details

### Technologies Used
- HTML5
- CSS3 (with animations and glassmorphism effects)
- Vanilla JavaScript (ES6+)

### Browser Support
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

### File Structure
```
marriage-eligibility-checker/
│
├── index.html          # Main HTML file (minified)
├── assests/
│   └── dragDropImg.png # Drag and drop placeholder image
└── README.md           # Documentation
```

## ⚡ Performance

- **Page Load**: < 1s
- **File Size**: ~8KB (minified)
- **No external dependencies**
- **Optimized animations using CSS transforms**

## 🎪 Fun Facts

- Random eligibility for image-based verification
- Age-based verification follows legal marriage age (18+)
- Includes a warning marquee about repeated checks
- Auto-reload feature for fresh checks

## 🐛 Known Issues

- Image upload requires placeholder image at `./assests/dragDropImg.png`
- Marquee tag used (deprecated but functional)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Ajaira Boy Adil**

## 🙏 Acknowledgments

- Inspired by modern web design trends
- Glassmorphism UI design
- Cyberpunk scanning animations

## 📞 Support

For support, email your-email@example.com or open an issue in the repository.

## 🔮 Future Enhancements

- [ ] Add more verification methods
- [ ] Integrate real facial recognition API
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Save results history
- [ ] Social media sharing

---

⭐ Star this repo if you find it helpful!

**Note**: This is a fun project and should not be used for actual marriage eligibility verification. Always consult with legal authorities for official matters.
```