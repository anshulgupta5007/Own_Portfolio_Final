# Developer Portfolio

A modern, responsive developer portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI** - Clean, professional design with smooth animations
- **Project Showcase** - Display your GitHub projects with live preview buttons
- **Skills Section** - Highlight your technical skills and expertise
- **Contact Form** - Functional contact form for visitor inquiries
- **Resume Page** - Opens in a new tab from the hero, contact, and footer sections
- **Local Preview Server** - Serve the portfolio and project previews on one local server

## File Structure

```
3_Own_Portfolio_Site/
├── index.html          # Main portfolio page
├── styles.css          # Styling and responsive design
├── assests
    └──| colors         # Background Image of WebApp
        └──| grabient-_gNVgK5gQgf89gBk.png
    └──| images         # Projects Reference
        └──| image-gallery.png
        └──| own-portfolio.png
        └──| simple-calculator.png
└── README.md
```

## Running Locally

Project previews and resume links can be opened using the local server but it is mainly operating using Vercel. Open the portfolio with: https://myportfolioproject-sigma.vercel.app/

Then visit:

- [Portfolio Link](https://anshulguptawebdevportfolio.vercel.app/)
- [Resume File](https://drive.google.com/file/d/1orrFA-jOw6rzRXKWa9XGOEckEOAFocE4/view?usp=sharing)

### Project Previews

| Project | Preview URL |
|---------|-------------|
| Image Gallery WebApp | https://code-alpha-image-gallery-woad.vercel.app/ |
| Basic Calculator | https://basic-calculator-xi-jet.vercel.app/ |
| Portfolio | https://anshulguptawebdevportfolio.vercel.app/ |

Click **Preview** on any project card to open its live demo in a new tab.

All the projects will be open in new tab for live preview.

## Contact Information

- **Email:** anshulmrt4@gmail.com
- **Phone:** +91 7417990944
- **GitHub:** [github.com/anshulgupta5007](https://github.com/anshulgupta5007/)
- **LinkedIn:** [linkedin.com/in/anshul-gupta4](https://www.linkedin.com/in/anshul-gupta4)

## Customization

### Adding Projects

1. Add a project card in `index.html`
2. Create a preview folder under `previews/` or under `PROJECTS`
3. Point the Preview button to `/preview/your-project-key/`

### Color Scheme

Modify the CSS variables in `styles.css`:

## Deployment

For production deployment (GitHub Pages, Netlify, Vercel), you will need to either:

- Deploy preview pages alongside the portfolio, or
- Link Preview buttons to live deployed URLs instead of `/preview/*` routes

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This portfolio template is free to use for personal and commercial projects.
