# Aime Serge Tuyishime - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my skills, experience, and projects as a Computer Science student specializing in Data Analytics.

## 🌐 Live Website

**URL:** [https://aime-moria.com](https://aime-moria.com)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Setup & Installation](#setup--installation)
- [Deployment](#deployment)
- [Contact Form Configuration](#contact-form-configuration)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## About

This is my personal portfolio website where I showcase my journey as a Computer Science student at Grand Canyon University. The site highlights my technical skills, professional experience, and provides a way for potential collaborators and employers to connect with me.

**Key Information:**
- **Name:** Aime Serge Tuyishime (also known as Aime Moria)
- **Field:** Computer Science & Data Analytics
- **University:** Grand Canyon University
- **Experience:** 3+ Years
- **Location:** United States

## Features

### Core Features
- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Dark/Light Mode Toggle** - User preference-based theme switching
- **Interactive Navigation** - Smooth scrolling between sections
- **Mobile Menu** - Hamburger menu for mobile navigation
- **Animated Background** - Particle network animation on home section
- **Contact Form** - Functional contact form with email integration
- **Social Links** - Direct links to social media profiles

### Sections
1. **Home** - Hero section with profile photo and introduction
2. **About** - Detailed biography with experience cards
3. **Skills** - Technical skills with expandable view
4. **Contact** - Contact form and social media links

### Technical Features
- Fixed navigation header with backdrop blur
- Form validation and EmailJS integration
- CSS animations and hover effects
- Font Awesome icons integration
- Google Fonts (Quicksand & Reenie Beanie)
- Cross-browser compatibility

## 🛠 Technologies Used

### Frontend
- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with flexbox/grid, gradients, and animations
- **JavaScript (ES6+)** - Interactive functionality and DOM manipulation

### Libraries & Services
- **EmailJS** - Contact form email functionality
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (Quicksand, Reenie Beanie)

### Hosting & Deployment
- **Firebase Hosting** - Static site hosting
- **Custom Domain** - Professional domain setup

### Development Tools
- Modern browser developer tools
- Git version control
- Firebase CLI

## 📁 File Structure

```
project-root/
├── main/                 # Public directory (Firebase hosting)
│   ├── css/
│   │   └── styles.css   # Main stylesheet
│   ├── js/
│   │   ├── script.js    # Main JavaScript functionality
│   │   └── emailjs.min.js # EmailJS SDK
│   ├── images/          # Website images
│   │   ├── profile.jpg  # Profile photo
│   │   ├── favicon.ico  # Website favicon
│   │   └── *.png        # Skill/feature icons
│   ├── files/
│   │   └── myresume.pdf   # Downloadable resume
│   └── index.html       # Main HTML file
├── firebase.json        # Firebase configuration
└── README.md           # Project documentation
```

## Setup & Installation

### Prerequisites
- Node.js and npm (for Firebase CLI)
- Git
- Web browser
- Text editor/IDE

### Local Development

1. **Clone the repository**
   ```bash
   git clone [your-repository-url]
   cd personal-website
   ```

2. **Open locally**
   - Open `main/index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python
   cd main
   python -m http.server 8000
   
   # Using Node.js
   npx serve main
   ```

3. **Make changes**
   - Edit HTML in `main/index.html`
   - Modify styles in `main/css/styles.css`
   - Update functionality in `main/js/script.js`

## 🌐 Deployment

### Firebase Hosting Setup

1. **Install Firebase CLI**
   ```bash
   npm install -g firebase-tools
   ```

2. **Login and initialize**
   ```bash
   firebase login
   firebase init hosting
   ```

3. **Deploy**
   ```bash
   firebase deploy
   ```

### Configuration Notes
- Public directory is set to `main/` in `firebase.json`
- Ignores: `firebase.json`, hidden files, `node_modules`
- Custom domain configured through Firebase console

## Contact Form Configuration

The contact form uses EmailJS for email functionality:

### EmailJS Setup
1. Create account at [EmailJS](https://www.emailjs.com/)
2. Set up email service (Gmail, Outlook, etc.)
3. Create email template with variables:
   - `{{name}}` - Sender's name
   - `{{contact_info}}` - Sender's email
   - `{{location}}` - Sender's location (optional)
   - `{{message}}` - Message content

### Configuration in script.js
```javascript
// Initialize EmailJS with your Public Key
emailjs.init('-hfbWk-2-MUzwJKl4'); // Replace with your key

// Send email configuration
emailjs.send('service_3mkn5sq', 'template_e8rlxer', emailData)
```

### Form Validation
- Email format validation
- Required field validation
- Message length validation (minimum 2 words)
- Success/error feedback display

## Customization

### Colors & Themes
- **Light Mode:** Blue gradient background with light content areas
- **Dark Mode:** Dark background with adjusted contrast
- **Accent Colors:** Various gradients for cards and buttons

### Typography
- **Headers:** Reenie Beanie (handwritten style)
- **Body Text:** Quicksand (clean, modern)
- **Navigation:** Quicksand with custom weights

### Animations
- **Particle Network:** Canvas-based animated background
- **Hover Effects:** Transform and shadow animations
- **Smooth Scrolling:** Navigation transitions

### Responsive Breakpoints
- **Desktop:** > 768px (full layout)
- **Mobile:** ≤ 768px (stacked layout, hamburger menu)

## Contact

**Aime Serge Tuyishime**
- **Website:** [https://aime-moria.com](https://www.aime-moria.com)
- **Email:** [220aime@gmail.com](mailto:220aime@gmail.com)
- **Phone:** [+1 (405) 926-6844](tel:+14059266844)
- **LinkedIn:** [linkedin.com/in/aimemoria](https://www.linkedin.com/in/aimemoria/)
- **Location:** United States

---

**Built with ❤️ by Aime Moria**