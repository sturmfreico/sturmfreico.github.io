# sturmfrei

**Finely crafted apps and tools for the web**

Welcome to the official repository for the Sturmfrei company website. We're a Sydney-based startup empowering e-commerce businesses with innovative Shopify apps and cutting-edge web tools for online success.

![sturmfrei Hero](./src/assets/images/screen.jpeg)

🌐 **Website:** [https://sturmfrei.com.au](https://sturmfrei.com.au)

## About Sturmfrei

Sturmfrei Pty Ltd is dedicated to building best-in-class applications and tools for the web. Our apps are built with best practices in mind, ensuring a seamless experience for you and your customers.

### Our Main Product

#### EasyEdit for Shopify

**Self-serve order editing! Empower your customers with complete control over their orders.**

EasyEdit is our flagship Shopify app that allows customers to edit their orders directly, reducing support tickets and improving customer satisfaction.

🔗 **Learn more:** [https://geteasyedit.com](https://geteasyedit.com)

**Key Features:**

- **Self-Service Order Editing:** Give customers the power to modify their orders without contacting support
- **Fulfillment Hold Workflow:** Pre-built Shopify Flow integration to automatically hold orders during the edit window
- **Customizable Edit Time Window:** Set your own time window for order edits (default: 30 minutes)
- **Easy Integration:** Simple setup process with guided onboarding
- **No Impact on Existing Orders:** Safe to install and uninstall without affecting current orders

## Technology Stack

This website is built with:

- **[Astro](https://astro.build/)** - Modern static site generator
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript

## Development

### Getting Started

From your terminal:

```sh
npm i
npm run dev
```

The site will be available at `localhost:4321`

### Building for Production

Create an optimized production build with:

```sh
npm run build
```

Preview the production build locally:

```sh
npm run preview
```

## Available Scripts

| Command               | Action                                             |
| :-------------------- | :------------------------------------------------- |
| `npm i`               | Installs dependencies                              |
| `npm run dev`         | Starts local dev server at `localhost:4321`        |
| `npm run build`       | Build your production site to `./dist/`            |
| `npm run preview`     | Preview your build locally, before deploying       |
| `npm run format`      | Format codes with Prettier                         |
| `npm run lint:eslint` | Run Eslint                                         |
| `npm run astro ...`   | Run CLI commands like `astro add`, `astro preview` |

## Configuration

### Basic Configuration

The main configuration file is located at: `./src/config.yaml`

### Customize Design

To customize fonts, colors, or other design elements, refer to:

- `src/components/CustomStyles.astro` - Custom component styles
- `src/assets/styles/tailwind.css` - Tailwind CSS configuration

### Content Management

Blog posts and content are managed through:

- `src/content/` - Content collections
- `public/decapcms/` - Decap CMS configuration

## Project Structure

```
/
├── public/          # Static assets
├── src/
│   ├── assets/      # Images, styles, fonts
│   ├── components/  # Reusable Astro components
│   ├── content/     # Blog posts and content collections
│   ├── layouts/     # Page layouts
│   ├── pages/       # Route pages
│   └── utils/       # Utility functions
└── package.json
```

## Deployment

This site is automatically deployed via GitHub Actions when changes are pushed to the main branch. See `.github/workflows/deploy.yml` for deployment configuration.

## Connect With Us

- 🐦 **Twitter:** [@sturmfreico](https://x.com/sturmfreico)
- 📸 **Instagram:** [@sturmfreico](https://www.instagram.com/sturmfreico/)
- 💻 **GitHub:** [sturmfreico](https://github.com/sturmfreico)
- 📧 **Email:** support@sturmfrei.com.au

## License

See [LICENSE.md](LICENSE.md) for details.

## Acknowledgements

This repository is based on [AstroWind](https://github.com/onwidget/astrowind) and customized to our requirements.

---

© 2025 Sturmfrei Pty Ltd · All rights reserved
