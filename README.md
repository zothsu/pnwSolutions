# PNW Solutions

## Open Source Development & Consulting

Empowering businesses through open source software solutions. We specialize in modern web development, community-driven innovation, and helping enterprises leverage the power of open source technologies.

## TODO

FIND TODO APP FOR GIT INEGRATION

-[ ] Move away from google fonts, download ones to use. Or what is the preferred method for accesibility?

-[ ] **Add carousel component to reviews.astro**
-[ ] Update contact page
   -[ ] Add to top, schedule 15min free btn
   -[ ] Change contact header to "Prefer the written word? Send us an email!"
-[ ] Mv favicon from public to src
-[x] Update favicon with Tree SVG

-[ ] Add to app.cal
   -[x] Digital Consultation
   -[ ] Web Design Package
      - Digital Consultation
      - Web Design Planning
      - Product Delivery
   -[ ] Digital Resouce Management
   -[ ] SECRET EVENT Website Update

-[ ] Add unlinked page for digital services
   -[ ] Add schedulable services
      -[ ] Digital Consultation
      -[ ] Web Design Package
      -[ ] Digital Resource Management (If you need updates to a site I did not build)
   -[ ] Create link to app.cal

## 🌟 What We Do

- **Web Development Consulting** - Expert guidance on modern frameworks, architecture, and best practices
- **Enterprise Solutions** - Helping businesses adopt and integrate open source tools
- **Community Education** - Sharing knowledge through our blog and community initiatives

## Tech Stack

- [Astro](https://astro.build/) - Modern static site generator for content-driven websites
- [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript development
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Alpine.js](https://alpinejs.dev/) - Lightweight JavaScript framework
- [React](https://reactjs.org/) - Component-based UI development
- [Vue.js](https://vuejs.org/) - Progressive JavaScript framework
- [Node.js](https://nodejs.org/) - Server-side JavaScript runtime
- And many more open source tools and frameworks

## Website Features

- **Performance Optimized** - Lightning-fast loading times with modern build tools
- **SEO-Friendly** - Optimized for search engines and social sharing
- **Responsive Design** - Beautiful experience across all devices
- **Dark Mode Support** - Automatic theme switching based on user preference
- **Accessibility First** - Built with web accessibility standards in mind
- **Developer Blog** - Insights and tutorials for the open source community
- **Image/Review Carousel** - Components slide across the screen with one in the middle enlarged

## Website Structure

```text
/
├── public/             # Static assets (favicons, images) TEMPORARY
├── src/
│   ├── assets/         # Images and design assets
│   ├── components/     # Reusable UI components
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   └── ...
│   ├── layouts/        # Page layouts
│   │   └── Layout.astro
│   ├── pages/          # Website routes
│   │   ├── index.astro      # Homepage
│   │   ├── blog/            # Developer blog
│   │   ├── company.astro    # About us
│   │   ├── contact.astro    # Contact form
│   │   └── ...
│   ├── scripts/        # JavaScript utilities
│   └── styles/         # Global styles and animations
├── astro.config.mjs    # Astro configuration
└── package.json        # Project dependencies
```

## 🔧 Development Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Install dependencies                             |
| `npm run dev`             | Start local dev server at `localhost:4321`      |
| `npm run build`           | Build production site to `./dist/`              |
| `npm run preview`         | Preview build locally before deploying          |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🎨 Design System

### Color Palette

Our website uses a carefully crafted color system defined in `src/styles/global.css`:

- **Primary**: Green-based colors for brand elements and CTAs
- **Secondary**: Slate colors for text and neutral elements  
- **Accent**: Purple colors for highlights and interactive elements
- **Warning**: Yellow colors for alerts and notifications

### Typography

Professional typography stack:

- **Sans**: Inter with system fallbacks for body text
- **Display**: Lexend with system fallbacks for headings

### Animations & Transitions

Smooth, purposeful animations enhance user experience:

- Fade In effects for content loading
- Slide Up animations for progressive disclosure
- Slide Down transitions for interactive elements
- Page transitions for seamless navigation

## 📞 Get In Touch

- **Website**: [pnwdigitalsolutions.com](https://pnwdigitalsolutions.com)
- **E-mail** [hello@pnwdigitalsolutions.com](mailto:hello@pnwdigitalsolutions.com)
- **Blog**: [/blog](/blog)
- **GitHub**: [@zothsu](https://github.com/zothsu)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
