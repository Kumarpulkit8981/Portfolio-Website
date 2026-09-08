# Kumar Pulkit - Personal Portfolio

A responsive personal portfolio website for Kumar Pulkit, a BCA student and frontend developer. The site presents education, skills, projects, internship experience, training, certificate details, and contact information.

<img src="images/my-photo.jpg" alt="Kumar Pulkit" width="260">

**Kumar Pulkit** is a BCA student and frontend developer building thoughtful, responsive digital experiences.


## ✨ Features

- **Museum-Quality Design**: Inspired by Louvre aesthetics
- **Light/Dark Theme Toggle**: Smooth transitions with elegant animations  
- **Fully Responsive**: Perfect on all devices from mobile to desktop
- **Interactive Elements**: 3D profile frame, typing animations, scroll effects
- **Professional Typography**: Playfair Display + Inter + Crimson Pro
- **Smooth Animations**: CSS custom properties with elegant transitions
- **Contact Form**: Client-side validation with an email-draft fallback
- **SEO Optimized**: Semantic HTML with proper meta tags
- **Resume**: View the formatted resume or download `resume.pdf`
- **Internship Experience**: SQROCK IT SOLUTION web development internship

## 🚀 Quick Start

### Step 1: Clone the Repository
```bash
git clone https://github.com/Kumarpulkit8981/Portfolio-Website.git

# Navigate to the project folder
cd Portfolio-Website
```

### Step 2: Run Locally
Use Live Server in VS Code or start a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

### Step 3: Customize Your Portfolio
Update the content in `index.html`, styles in `styles.css`, and interactions in `script.js`.
Keep private internship letters and sensitive credentials out of the public repository.

#### `index.html` - Update Your Information:
```html
<!-- Change your name -->
<h1 class="name-main">Your Name</h1>

<!-- Update your role -->
<span class="role-main" id="roleText">Your Title</span>

<!-- Add your description -->
<p class="hero-description">Your personalized description...</p>

<!-- Update contact information -->
<p>kumarpulkit734@gmail.com</p>
<p>Your City, State, Country</p>

<!-- Add your social links -->
<a href="https://github.com/yourusername" class="social-link" data-platform="github">
<a href="https://linkedin.com/in/yourusername" class="social-link" data-platform="linkedin">
```

#### `styles.css` - Customize Colors:
```css
:root {
    /* Change accent colors to match your brand */
    --accent-primary: #your-color;
    --accent-secondary: #your-color;
    --accent-tertiary: #your-color;
}
```

#### Add Your Projects:
Replace the placeholder projects with your own work, update images, descriptions, and tech stacks.

#### Add Your Skills:
Update the skills section with your technologies and adjust the progress percentages.

### Step 4: Deploy with GitHub Pages
1. Push your changes to GitHub:
```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```
2. Open **Settings > Pages** in the GitHub repository.
3. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Expected site URL: `https://kumarpulkit8981.github.io/Portfolio-Website/`.

## 📁 File Structure

```
Portfolio-Website/
│
├── index.html          # Main HTML file
├── styles.css          # All styling (museum-quality CSS)
├── script.js           # Interactive functionality
├── resume.html          # Viewable and printable resume
├── resume.css           # Resume styles
├── resume.pdf           # Downloadable resume
├── images/              # Profile and project images
└── README.md            # Project documentation
```

## 🎨 Customization Guide

### Colors
The template uses CSS custom properties. Change the accent colors in `:root`:
```css
--accent-primary: #8b6f47;    /* Warm Bronze */
--accent-secondary: #6b5b73;  /* Muted Aubergine */  
--accent-tertiary: #7c8471;   /* Sage Green */
```

### Typography  
Three font families are used:
- **Headings**: Playfair Display (elegant serif)
- **Body**: Inter (clean sans-serif)
- **Accents**: Crimson Pro (readable serif)

### Sections
- **Hero**: Your introduction and main CTA
- **About**: Personal introduction, career goal, and toolkit
- **Education**: Qualifications, certificate, training, and internship experience
- **Projects**: Showcase five projects, including the SQROCK internship project
- **Skills**: Technical skills with progress bars
- **Contact**: Contact form + your information

### Theme Toggle
The light/dark theme toggle is fully functional. Colors automatically adjust using CSS custom properties.

## 🛠️ Development Tips

### Adding New Sections
Follow the existing pattern:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <div class="section-header">
            <div class="section-number">05</div>
            <h2 class="section-title">
                <span class="title-word">New</span>
                <span class="title-word">Section</span>
            </h2>
        </div>
        <!-- Your content -->
    </div>
</section>
```

### Adding Animations
Use the `.fade-in` class on elements you want to animate on scroll:
```html
<div class="my-element fade-in">Content</div>
```

### Performance
- All animations use `transform` and `opacity` for smooth 60fps performance
- Images are optimized with proper `loading="lazy"` where appropriate
- CSS uses efficient selectors and minimal repaints

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

Found a bug or want to contribute? 

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -am 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Created By

** Kumar Pulkit **

- GitHub: [@kumarpulkit8981](https://github.com/kumarpulkit8981)


## 🙏 Acknowledgments

- Inspired by Harvey.ai's clean aesthetics
- Museum design principles from Louvre's digital presence
- Typography choices inspired by editorial design
- Color palette based on warm, professional tones

---

**⭐ If this template helped you create an amazing portfolio, don't forget to star this repository!**

Happy coding! 🚀
