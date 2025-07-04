# Parth Suryawanshi's Modern Portfolio Website

A modern, responsive portfolio website showcasing software engineering projects, skills, and achievements. Built with HTML, CSS, and JavaScript featuring dark/light theme toggle, smooth animations, and mobile-first design.

## 👨‍💻 About

**Parth Suryawanshi** - Software Engineer  
📧 parthsuryawanshi001@gmail.com  
📞 +91 8459471544  
📍 Pune, Maharashtra, India  

Final-year Computer Science student at Dr. D. Y. Patil ACS College with a passion for software and web development. Currently pursuing MCA at MIT World Peace University.

## 🏆 Achievements

- 🥇 **1st Rank** - Avishkar Competition (Pune College Level)
- 📄 **Published Research Paper** - "Automated Waste Garbage Separation using Arduino and Sensors" in IJRAR (Impact Factor: 7.17)
- 🎓 **CGPA: 7.89** - B.Sc. Computer Science

## 🚀 Quick Start

1. **Clone or Download** this repository
2. **Add Your Content**:
   - Replace `assets/images/profile-placeholder.txt` with your profile photo (`profile.jpg`)
   - Replace `assets/images/project-placeholder.txt` with your project screenshot (`veer-sahayata.jpg`)
   - Replace `assets/resume-placeholder.txt` with your resume PDF (`resume.pdf`)
3. **Update Information**:
   - Edit personal details in `index.html`
   - Add your social media links
   - Update project details and GitHub links
4. **Open** `index.html` in your web browser

## 📁 Project Structure

```
Portfolio/
├── index.html                 # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css         # Main stylesheet with themes
│   ├── js/
│   │   └── script.js         # JavaScript functionality
│   ├── images/
│   │   ├── profile.jpg       # Your profile photo (add this)
│   │   └── veer-sahayata.jpg # Project screenshot (add this)
│   └── resume.pdf            # Your resume (add this)
└── README.md                 # This file
```

## 🎨 Customization

### Colors & Theme
- Edit CSS variables in `:root` and `[data-theme="dark"]` sections
- Primary color: `--primary-color`
- Secondary color: `--secondary-color`
- Background colors: `--bg-primary`, `--bg-secondary`, `--bg-tertiary`

### Content Updates
1. **Personal Information**: Update name, title, bio in `index.html`
2. **Skills**: Modify skill categories and tags in the skills section
3. **Projects**: Add new project cards or update existing ones
4. **Social Links**: Update href attributes for LinkedIn, GitHub, etc.

### Adding New Sections
1. Add new section HTML in `index.html`
2. Add corresponding styles in `style.css`
3. Update navigation menu with new link

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Grid, Flexbox, Custom Properties, Animations
- **JavaScript**: ES6+, Intersection Observer, Local Storage
- **External Libraries**:
  - Google Fonts (Poppins)
  - Font Awesome Icons
  - AOS (Animate On Scroll)

## ✨ Special Features

### Theme Toggle
- Automatically saves user preference
- Smooth transition between themes
- Icon changes based on current theme

### Typing Animation
- Multiple rotating text phrases
- Realistic typing speed with pauses
- Customizable text array

### Contact Form
- Client-side validation
- Success/error notifications
- Email format validation

### Accessibility
- Semantic HTML structure
- Keyboard navigation support
- Screen reader friendly
- High contrast ratios

## 💼 Featured Projects

### 1. **OneShot - Disposable Online Camera**
- **Tech Stack**: PHP, MySQL, JavaScript, HTML/CSS
- **Description**: Time-limited media sharing platform with 24-hour access, role-based uploads, and admin controls
- **Features**: Ephemeral sharing, user management, secure file handling

### 2. **MediSync - Healthcare Dashboard**
- **Tech Stack**: PHP, JavaScript, MySQL, Excel Integration
- **Description**: Healthcare dashboard for tracking patient metrics and generating insights
- **Features**: Real-time analytics, data visualization, multi-source integration

### 3. **Automated Doctor Dustbin (IoT)**
- **Tech Stack**: Arduino, IoT Sensors, Servo Motor, C++
- **Description**: Smart dustbin with waste level detection and automated alerts
- **Achievement**: Published research paper in IJRAR (Impact Factor: 7.17)

### 4. **Veer Sahayata - Defence Welfare Portal**
- **Tech Stack**: React, PHP, MySQL, Chart.js
- **Description**: Web portal for Indian Defence personnel and families
- **Features**: Pension tracking, news updates, document verification

## 🛠️ Technical Skills

- **Programming**: PHP, Java, Python, C
- **Web Technologies**: HTML5, CSS3, JavaScript, React
- **Databases**: MySQL, PostgreSQL
- **Tools**: Git, GitHub, Arduino, Microsoft 365 Copilot

## 📜 Certifications

- Introduction to Programming using Java & DSA
- Development using HTML5 and JavaScript
- Learning Microsoft 365 Copilot
- Microsoft Copilot: The Art of Prompt Writing
- Deloitte Australia – Data Analytics Job Simulation

## 🌟 Portfolio Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Dark/Light Theme**: Toggle between themes with persistent storage
- **Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **Smooth Scrolling**: Elegant navigation with scroll indicators
- **Typing Animation**: Dynamic hero text with multiple phrases
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Optimized assets and efficient code

## 📧 Contact Form Setup

The contact form currently shows success messages locally. To make it functional:

1. **Backend Integration**: Connect to a backend service (Node.js, PHP, etc.)
2. **Email Services**: Use services like EmailJS, Netlify Forms, or Formspree
3. **Validation**: Server-side validation for security

### Example with EmailJS:
```javascript
// Add to script.js
emailjs.send('service_id', 'template_id', {
    name: name,
    email: email,
    message: message
}).then(() => {
    showNotification('Message sent successfully!', 'success');
});
```

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch (main/master)
4. Your site will be available at `username.github.io/repository-name`

### Netlify
1. Connect GitHub repository to Netlify
2. Auto-deploy on every push
3. Custom domain support

### Vercel
1. Import GitHub repository
2. Automatic deployments
3. Free custom domains

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, consider sharing them back!

## 📞 Support

If you need help customizing this portfolio:
- Check the code comments for guidance
- Refer to CSS/JS documentation
- Create an issue in the repository

---

**Built with ❤️ by Parth**

*Last updated: July 2025*
