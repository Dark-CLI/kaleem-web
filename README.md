# Kaleem Website

This project is the official website for Kaleem Smart Home Solutions, built with the Astro web framework and deployed on Cloudflare Pages. It showcases our services, solutions, and company information.

## ✨ Features

*   **Multi-language Support:** Available in both English and Arabic, with dynamic language switching.
*   **Dark Mode:** User-toggleable light and dark themes for comfortable viewing.
*   **Responsive Design:** Optimized for various screen sizes and devices.
*   **Clean & Modern UI:** Polished design with subtle animations and consistent styling.
*   **SEO Friendly:** Configured for better search engine visibility (sitemap pending URL update).

## 🚀 Project Structure

*   `src/pages/`: Website pages (Markdown and Astro components), organized by language (`en/`, `ar/`).
*   `src/components/`: Reusable Astro components (e.g., Header, Footer, Language Switcher, Theme Toggle).
*   `src/layouts/`: Layout components for consistent page structure.
*   `src/i18n/`: Translation files for UI strings (`en.json`, `ar.json`).
*   `public/`: Static assets like images and fonts.
*   `src/styles/`: Global CSS styles.

## 🧞 Commands

All commands are run from the root of the project in a terminal:

| Command                 | Action                                         |
| :---------------------- | :--------------------------------------------- |
| `npm install`           | Installs project dependencies.                  |
| `npm run dev`           | Starts the local development server.           |
| `npm run build`         | Builds the site for production.                |
| `npm run preview`       | Previews the production build locally.         |
| `npm run deploy`        | Deploys the site to Cloudflare Pages.          |

## 🌐 Multi-language Setup

The website supports English (default) and Arabic. Language-specific content is located in `src/pages/en/` and `src/pages/ar/`. UI strings are managed in `src/i18n/`.

## 👀 Want to learn more?

Check out the [Astro documentation](https://docs.astro.build) to learn more about the framework.
