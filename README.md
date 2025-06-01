# Jose Hernandez Hoyos - Portfolio

My personal portfolio website built with modern web technologies, showcasing my experience as a Senior Software Developer. The site features a clean, responsive design with smooth animations and dark mode support.

## 🚀 Features

- Responsive design with modern UI/UX principles
- Dark/Light mode theme switching
- Smooth scroll animations using AOS
- Interactive components with GSAP animations
- Contact form integration
- Projects section (🚧 In Progress)

## 💻 Technologies Used

- [Astro](https://astro.build/) - Static Site Generator
- [TailwindCSS](https://tailwindcss.com/) - Styling
- [TypeScript](https://www.typescriptlang.org/) - Type Safety
- [AOS](https://michalsnik.github.io/aos/) - Scroll Animations
- [GSAP](https://greensock.com/gsap/) - Advanced Animations
- [Inter](https://fonts.google.com/specimen/Inter) & [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) - Typography

## 🛠️ Project Structure

```text
/
├── public/          # Static assets
├── src/
│   ├── assets/      # Project images and media
│   ├── components/  # Reusable UI components
│   ├── layouts/     # Page layouts
│   ├── pages/       # Route pages
│   └── styles/      # Global styles
└── package.json
```

## ⚙️ Development

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build

# Preview production build
pnpm preview
```

## 🔄 Current Status

The portfolio is actively being developed with most core features implemented. The Projects section is currently under construction and will be added soon with detailed showcases of my work.

## 📝 License

All rights reserved - Jose Hernandez Hoyos (Because it's me)

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
