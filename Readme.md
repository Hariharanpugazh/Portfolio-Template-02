# Portfolio Template

A modern, responsive portfolio template built with Next.js, TypeScript, and Tailwind CSS. This template is designed for developers, AI engineers, and data scientists to showcase their projects, skills, and professional experience.

## Live Demo
Check out the live demo: **[harlee.vercel.app](https://harlee.vercel.app)**

![Next.js](https://img.shields.io/badge/Next.js-13.x-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-4.9-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=flat-square&logo=tailwind-css)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## Features

- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Dark Theme** - Modern dark color scheme with elegant typography
- **Smooth Animations** - Built with Framer Motion for fluid user interactions
- **Project Showcase** - Grid layout for displaying your work with live demos and repository links
- **Skills Section** - Interactive display of technologies and tools
- **Timeline Experience** - Professional experience timeline with animations
- **Contact Form** - Integrated contact form with Formspree
- **SEO Optimized** - Built-in meta tags and structured data
- **Fast Performance** - Optimized with Next.js for lightning-fast loading

## Tech Stack

### Frontend
- **Next.js 13** - React framework with App Router
- **TypeScript** - Type-safe JavaScript development
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library for React

### UI Components
- **Mantine** - Modern React components library
- **FontAwesome** - Icon library for tech stack display
- **Heroicons** - Beautiful hand-crafted SVG icons

### Development Tools
- **ESLint** - Code linting and formatting
- **Prettier** - Code formatting
- **PostCSS** - CSS processing

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Hariharanpugazh/Portfolio-Template-02.git
   cd Portfolio-Template-02
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## Customization

### Personal Information
Update your personal details in the following files:
- `components/content/Hero.tsx` - Name and professional title
- `components/content/AboutMe.tsx` - Personal description
- `components/content/ContactMe.tsx` - Contact information
- `package.json` - Author details and repository

### Skills and Technologies
Modify your tech stack in:
- `components/utils/mySkills.ts` - Add/remove skills categories
- `components/icons/AllFavTechs.tsx` - Update favorite technologies

### Projects
Add your projects in:
- `components/sections/ProjectsSection.tsx` - Update project data
- `components/content/FavProjects.tsx` - Featured projects
- `/public/` - Add project images

### Styling
- `tailwind.config.js` - Customize colors, fonts, and spacing
- `styles/globals.css` - Global styles and custom CSS

## Project Structure

```
├── app/
│   ├── (user)/          # Main application routes
│   └── head.tsx         # Document head configuration
├── components/
│   ├── content/         # Page content components
│   ├── icons/           # Icon components
│   ├── projects/        # Project-related components
│   ├── sections/        # Main page sections
│   ├── ui/              # Reusable UI components
│   └── utils/           # Utility components
├── hooks/               # Custom React hooks
├── public/              # Static assets
├── styles/              # CSS files
└── types/               # TypeScript type definitions
```

## Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with zero configuration

### Other Platforms
```bash
npm run build
npm start
```

## Configuration

### Contact Form
The template uses Formspree for contact form handling. Update the form action in `components/content/ContactMe.tsx`:
```tsx
<form action='https://formspree.io/f/YOUR_FORM_ID' method='POST'>
```

### Environment Variables
Create a `.env.local` file for any environment-specific configurations:
```bash
NEXT_PUBLIC_SITE_URL=https://yoursite.com
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- **Lighthouse Score**: 95+ for Performance, Accessibility, Best Practices, and SEO
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s

## Contributing

This is an open-source template. Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Hariharan P**
- Email: hariharanpugazh@gmail.com
- GitHub: [@Hariharanpugazh](https://github.com/Hariharanpugazh)

## Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Animations by [Framer Motion](https://www.framer.com/motion/)
- Icons from [FontAwesome](https://fontawesome.com/) and [Heroicons](https://heroicons.com/)

---

⭐ Star this repository if you found it helpful!
