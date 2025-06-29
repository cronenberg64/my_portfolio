# Jonathan Setiawan - Portfolio

A modern, responsive portfolio website showcasing Jonathan Setiawan's work as a student and aspiring developer.

## Features

- Modern, glassmorphism design
- Interactive 3D planet background using Three.js
- Fully responsive design
- Smooth animations and transitions
- SEO optimized
- Security headers configured

## Local Development

1. Clone the repository:
```bash
git clone <your-repo-url>
cd my_portfolio
```

2. Install dependencies (if any):
```bash
npm install
```

3. Start a local server (optional, for static HTML):
```bash
npx serve public
```

4. Open your browser and navigate to `http://localhost:3000` (or the port shown)

## Deployment on Netlify

This project is configured for easy deployment on Netlify:

1. **Ensure all your static files (including `index.html` and `profile_picture.jpg`) are in the `public` directory.**
2. Push your code to GitHub.
3. Go to [Netlify](https://app.netlify.com/) and create a new site from Git.
4. When prompted for build settings, use:
   - **Base directory:** *(leave blank)*
   - **Build command:** *(leave blank)*
   - **Publish directory:** `public`
5. Click "Deploy site".

Your site will be live at a Netlify URL, and all static assets in `public` (including your profile picture) will be served correctly.

## Project Structure

```
my_portfolio/
├── public/
│   ├── index.html          # Main HTML file
│   ├── profile_picture.jpg # Profile picture
│   └── ...                # Other static assets
├── package.json            # Project dependencies and scripts
├── README.md               # Project documentation
└── ...
```

## Customization

To customize this portfolio for your own use:

1. Update the personal information in `public/index.html`
2. Replace the profile picture in `public/profile_picture.jpg`
3. Update the projects section with your own work
4. Modify the color scheme in the CSS variables
5. Update the contact form to point to your preferred contact method

## Connect With Me

- GitHub: [@cronenberg64](https://github.com/cronenberg64)
- LinkedIn: [Jonathan Setiawan](https://www.linkedin.com/in/jonathans1902/)
- Email: [jonathanrustam2@gmail.com]

## License

MIT License - feel free to use this template for your own portfolio! 