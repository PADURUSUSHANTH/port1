# Sushanth Reddy Paduru - Portfolio Website

This repository contains a responsive portfolio website for Sushanth Reddy Paduru, showcasing skills, experience, projects, and contact information.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Interactive navigation with smooth scrolling
- Skills section with animated progress bars
- Timeline-based experience section
- Project showcase with technology tags
- Contact form (static implementation)
- Modern, professional design with customized color scheme

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Media Queries)
- JavaScript (Vanilla)
- Font Awesome for icons
- Google Fonts

## Deployment Instructions

### GitHub Pages Deployment

1. **Fork or Clone this Repository**
   - Click the "Fork" button at the top right of this page, or
   - Clone the repository to your local machine:
     ```
     git clone https://github.com/yourusername/portfolio.git
     ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll down to the "GitHub Pages" section
   - Select the branch you want to deploy (usually `main` or `master`)
   - Click "Save"
   - Your site will be published at `https://yourusername.github.io/portfolio/`

3. **Customize the Content**
   - Update the information in `index.html` to reflect your personal details
   - Modify the styling in `css/styles.css` if desired
   - Add your own projects and experiences
   - Replace placeholder profile image with your photo

### Local Development

1. **Clone the Repository**
   ```
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Open in Browser**
   - Simply open the `index.html` file in your web browser to view the site locally

3. **Make Changes**
   - Edit the HTML, CSS, and JavaScript files as needed
   - Refresh your browser to see changes

## File Structure

```
portfolio/
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── script.js           # JavaScript functionality
├── images/                 # Directory for images
└── README.md               # This file
```

## Customization

### Colors

The website uses a color scheme defined by CSS variables in the `:root` selector in `styles.css`. You can easily change these colors to match your personal brand:

```css
:root {
    --primary-color: #2563eb;    /* Royal Blue */
    --secondary-color: #0f172a;  /* Dark Navy */
    --accent-color: #f97316;     /* Orange */
    --light-bg: #f8fafc;         /* Off-white */
    --dark-bg: #1e293b;          /* Slate */
    --text-primary: #0f172a;     /* Dark Navy */
    --text-secondary: #64748b;   /* Slate Gray */
    --text-light: #f8fafc;       /* Off-white */
}
```

### Fonts

The website uses Google Fonts. You can change these in the `<head>` section of `index.html` and update the font-family references in `styles.css`.

## License

This project is available for personal use and can be modified as needed.

## Contact

For any questions or suggestions, please contact:
- Email: padurusushanth@gmail.com
- LinkedIn: [Sushanth Reddy Paduru](https://linkedin.com/in/sushanth-reddy-paduru)
