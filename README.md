# Yang Chao Lab Website

A professional academic research lab website built with Jekyll and GitHub Pages.

## Features

- **Home Page**: Lab introduction and news
- **Research**: Current research projects and focus areas
- **Team**: Lab members and alumni
- **Publications**: Research publications and preprints
- **Contact**: Lab contact information and inquiries
- **Responsive Design**: Works on desktop and mobile devices
- **Academic Professional Styling**: Clean, professional appearance suitable for academic institutions

## Getting Started

### Local Development

1. Install Ruby and Jekyll:
   ```bash
   gem install jekyll bundler
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/cyangNYU/yang_lab.github.io.git
   cd yang_lab.github.io
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```

5. Visit `http://localhost:4000` in your browser

## Customization

Edit the following files to customize your site:

- **`_config.yml`**: Site configuration, title, URL, social links
- **`index.md`**: Home page content
- **`research.md`**: Research overview and projects
- **`team.md`**: Team member information
- **`publications.md`**: Publications list
- **`contact.md`**: Contact information
- **`assets/css/style.css`**: Styling and colors

### Adding Content

1. **Update Team Members**: Edit `team.md` with actual names, emails, and bios
2. **Add Publications**: Edit `publications.md` with your publications, ordered by year
3. **Update Research**: Edit `research.md` with your research projects
4. **Customize Colors**: Edit `assets/css/style.css` (main color: `#004d99`)

## GitHub Pages Deployment

Your site will be automatically deployed to GitHub Pages when you push to the `main` branch:

- Site URL: `https://cyangNYU.github.io/yang_lab.github.io`

## File Structure

```
.
├── _config.yml          # Site configuration
├── _layouts/            # HTML templates
│   ├── default.html
│   └── home.html
├── assets/
│   └── css/
│       └── style.css    # Professional styling
├── index.md             # Home page
├── research.md          # Research page
├── team.md              # Team page
├── publications.md      # Publications page
├── contact.md           # Contact page
└── README.md            # This file
```

## Color Scheme

- **Primary Blue**: `#004d99` (professional academic blue)
- **Dark Blue**: `#003366` (hover states)
- **Background**: `#fafafa` (light gray)
- **Text**: `#333` (dark gray)
- **Accent**: White with subtle shadows

## Support

For GitHub Pages documentation, visit: https://pages.github.com/

For Jekyll documentation, visit: https://jekyllrb.com/

---

**Last Updated**: May 2026
