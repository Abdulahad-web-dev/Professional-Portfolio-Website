# Professional Portfolio Website

A modern, responsive portfolio website showcasing the work and skills of Abdulahad, a Front-End Web Developer. This website features a sleek design with dark/light theme support, smooth animations, and fully functional sections.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on all devices
- **Dark/Light Theme**: Toggle between dark and light themes with smooth transitions
- **Modern Animations**: Smooth scrolling, particle effects, and interactive elements
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Dynamic project cards with live demo links
- **Skills Section**: Animated skill bars showing proficiency levels
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Social Links**: Integrated social media links in footer

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: Advanced styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)**: Modern JavaScript with DOM manipulation and event handling
- **Font Awesome**: Icon library for social media and UI icons
- **Google Fonts**: Poppins and Raleway fonts for typography
- **LocalStorage**: Theme preference persistence

## 📁 Project Structure

```
Professional-Portfolio-Website/
├── index.html          # Main HTML file (329 lines)
├── style.css           # Complete styling (1,177 lines)
├── script.js           # JavaScript functionality (248 lines)
├── profile.png         # Profile image
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Abdulahad-web-dev/Professional-Portfolio-Website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Professional-Portfolio-Website
   ```

3. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

## 📐 Sections Overview

### 1. Hero Section
- Eye-catching introduction with animated text
- Profile image display
- Call-to-action buttons
- Particle background effect

### 2. About Section
- Personal introduction and background
- Skill proficiency bars with animations
- Professional summary

### 3. Projects Section
- Featured projects with live demos
- Project cards with hover effects
- Technology tags for each project
- Links to live demos and details

#### Featured Projects:
1. **CUI Vehari Campus Portal**
   - University informational portal
   - Technologies: HTML5, CSS3, JavaScript, GitHub

2. **VSpark Pharmacy Manager**
   - Comprehensive pharmacy management system
   - Features: Upload functionality, receipt generation
   - [Live Demo](https://abdulahadwarraichweb-debug.github.io/Medical-Store-Managment-System/)

3. **Amazon Clone**
   - Responsive e-commerce website clone
   - Features: Product listings, modern UI
   - [Live Demo](https://abdulahadwarraichweb-debug.github.io/Amazon---clone/)

### 4. Contact Section
- Contact information display
- Functional contact form
- Location, email, and phone details
- Social media integration

## 🎨 Design Features

### Color Scheme
- **Primary**: #6C63FF (Purple)
- **Secondary**: #4A44C6 (Dark Purple)
- **Dark Theme**: #121212 background
- **Light Theme**: #FFFFFF background

### Typography
- **Primary Font**: Poppins (300-800 weights)
- **Secondary Font**: Raleway (300-800 weights)

### Animations
- Smooth scroll behavior
- Hover effects on interactive elements
- Theme transition animations
- Mobile menu animations
- Skill bar animations on scroll

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🔧 Customization

### Changing Theme Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary: #6C63FF;
    --primary-light: #8A84FF;
    --secondary: #4A44C6;
    /* Add your custom colors */
}
```

### Adding New Projects
1. Duplicate a project card in the HTML
2. Update the project information
3. Add appropriate tags and links

### Updating Skills
Modify the skill items in the About section:
```html
<div class="skill-item">
    <div class="skill-info">
        <span class="skill-name">Your Skill</span>
        <span class="skill-percent">85%</span>
    </div>
    <div class="skill-bar" data-skill="85"></div>
</div>
```

## 🌐 Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📧 Contact Information

- **Name**: Abdulahad
- **Email**: abdulahadwarraich.web@gmail.com
- **Phone**: 03000479696
- **Location**: Vehari, Pakistan

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌟 Live Demo

View the live portfolio [here](https://abdulahad-web-dev.github.io/Professional-Portfolio-Website/) (replace with actual deployment URL).

## 🔗 Social Links

- GitHub: [Abdulahad-web-dev](https://github.com/Abdulahad-web-dev)
- LinkedIn: [Add your LinkedIn profile]
- Twitter: [Add your Twitter profile]
- Dribbble: [Add your Dribbble profile]

## 📊 Project Stats

- **Total Lines of Code**: ~1,754 lines
- **HTML**: 329 lines
- **CSS**: 1,177 lines  
- **JavaScript**: 248 lines
- **Image Assets**: 1 (profile.png)

## 🔄 Version History

- **v1.0.0** - Initial release with basic portfolio features
- **v1.1.0** - Added dark/light theme toggle
- **v1.2.0** - Enhanced mobile responsiveness
- **v1.3.0** - Added particle background effects

---

**Built with ❤️ by Abdulahad**

*Last updated: April 2026*