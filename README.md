# Simon Marcus V. Reyes - CV & Portfolio Website

A modern, responsive personal CV and portfolio website built with HTML, CSS, and JavaScript. This website showcases professional experience, skills, projects, and provides a contact form for potential clients or employers.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Mobile-friendly hamburger menu
  - Animated skill bars
  - Typing effect on hero section
  - Scroll-triggered animations
  - Back to top button
- **Sections**:
  - Hero section with call-to-action buttons
  - About section with statistics
  - Work experience timeline
  - Skills with progress bars
  - Featured projects showcase
  - Contact form with validation
- **Performance Optimized**: Fast loading with optimized assets

## 🚀 Live Demo

[View Live Website](https://simonvreyes.github.io/cv-profile/)

## 📁 Project Structure

```
cv-profile/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter font family)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎨 Customization

### Personal Information
Update the following in `index.html`:

1. **Name and Title**: Change "Simon Marcus" and "Software Developer & Technology Enthusiast"
2. **About Section**: Modify the description and statistics
3. **Experience**: Update work history, companies, and dates
4. **Skills**: Adjust skill levels and add/remove skills
5. **Projects**: Replace with your own projects
6. **Contact Information**: Update email, phone, and location

### Styling
Modify `styles.css` to customize:
- Color scheme (primary color: #2563eb)
- Typography
- Layout spacing
- Animations

### Functionality
Edit `script.js` to customize:
- Animation timings
- Form handling
- Interactive features

## 🚀 Deployment to GitHub Pages

### Step-by-Step Guide

1. **Create a GitHub Repository**
   ```bash
   # If you haven't already, create a new repository on GitHub
   # Name it: cv-profile
   ```

2. **Initialize Git and Push to GitHub**
   ```bash
   # Navigate to your project directory
   cd /path/to/cv-profile
   
   # Initialize git (if not already done)
   git init
   
   # Add all files
   git add .
   
   # Commit changes
   git commit -m "Initial commit: CV and portfolio website"
   
   # Add remote repository (replace 'your-username' with your GitHub username)
   git remote add origin https://github.com/your-username/cv-profile.git
   
   # Push to GitHub
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your GitHub repository
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Website**
   - Your website will be available at: `https://your-username.github.io/cv-profile/`
   - It may take a few minutes for the changes to propagate

### Alternative: Using GitHub CLI

If you have GitHub CLI installed:

```bash
# Create repository and push in one command
gh repo create cv-profile --public --source=. --remote=origin --push
```

## 🔧 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/cv-profile.git
   cd cv-profile
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

3. **Make changes and test locally**

## 📝 Customization Checklist

Before deploying, make sure to update:

- [ ] Your name and title
- [ ] About section content
- [ ] Work experience details
- [ ] Skills and proficiency levels
- [ ] Project descriptions and links
- [ ] Contact information
- [ ] Social media links
- [ ] Profile picture (replace placeholder)
- [ ] Color scheme (if desired)
- [ ] Meta tags for SEO

## 🎯 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Responsive design
- Fast loading times
- Accessible navigation

## 📧 Contact Form

The contact form currently shows a success message. To make it functional:

1. **Option 1: Use a form service**
   - Netlify Forms
   - Formspree
   - EmailJS

2. **Option 2: Backend integration**
   - Node.js/Express
   - PHP
   - Python/Flask

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for stock images (if used)
- The open-source community for inspiration

---

**Happy coding! 🚀**
