# SoCraTes Canada

🚀 [Website](https://socrates-ca.github.io/)

## How to update the website?

### Setup

Pre-requisites:
- [Node.js](https://nodejs.org/en)
  - The version is specified in [.nvmrc](./.nvmrc)
  - You can use [nvm](https://github.com/nvm-sh/nvm) to switch to the correct version

Once you are ready, install dependencies with:

    npm ci

> [!INFO]
> The website is built with [Astro](https://astro.build/), based on the [Accessible Astro Starter](https://github.com/markteekman/accessible-astro-starter) template. The source code is in [TypeScript](https://www.typescriptlang.org/). It uses [Tailwind](https://tailwindcss.com/) for the design.

### Run the website locally

Run this command:

    npm start

Then, open the link that's provided to you.

### Other commands

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

### Deploy changes

Once pushed to `main`, the changes are automatically deployed online via [GitHub Actions](https://github.com/socrates-ca/socrates-ca.github.io/actions).

## ♿ (Accessibility) Features

- Astro 4.0
- Tailwind CSS support
- Prettier integration with `prettier-plugin-astro` and `prettier-plugin-tailwind`
- ESLint integration with strict accessibility settings for `eslint-plugin-jsx-a11y`
- Markdown and MDX support with examples included in the theme
- Uses the awesome `astro-icon` package for the icons
- Excellent Lighthouse/PageSpeed scores
- Accessible landmarks such as `header`, `main`, `footer`, `section` and `nav`
- Outline focus indicator which works on dark and light backgrounds
- Several `aria` attributes which provide a better experience for screen reader users
- `[...page].astro` and `[post].astro` demonstrate the use of dynamic routes and provide a basic blog with breadcrumbs and pagination
- `404.astro` provides a custom 404 error page which you can adjust to your needs
- `Header.astro` component included in the `DefaultLayout.astro` layout
- `Footer.astro` component included in the `DefaultLayout.astro` layout
- `SkipLinks.astro` component to skip to either the main menu or the main content
- `Navigation.astro` component with keyboard accessible (dropdown) navigation (arrow keys, escape key)
- `ResponsiveToggle.astro` component with an accessible responsive toggle button for the mobile navigation
- `DarkMode.astro` component toggle with accessible button and a user system preferred color scheme setting
- `SiteMeta.astro` SEO component for setting custom meta data on different pages
- `.sr-only` utility class for screen reader only text content (hides text visually)
- `prefers-reduced-motion` disables animations for users that have this preference turned on
- Ships with many components such as Accordions, Breadcrumbs, Modals, Pagination [and many more](https://accessible-astro.dev/accessible-components)
- A collection of utility classes such as breakpoints, button classes, font settings, resets and outlines in `src/assets/scss/base`
- View Transitions (⚠️ see [astro-docs](https://docs.astro.build/en/guides/view-transitions/#accessibility) for accessibility considerations)

## 🚀 Getting started

Clone this theme locally and run any of the following commands in your terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:4321`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 📦 Other Accessible Astro projects

- [Accessible Astro Dashboard](https://github.com/markteekman/accessible-astro-dashboard/)
- [Accessible Astro Components](https://github.com/markteekman/accessible-astro-components/)

## ❤️ Helping out

If you find that something isn't working right then I'm always happy to hear it to improve this starter! You can contribute in many ways and forms. Let me know by either:

1. [Filing an issue](https://github.com/markteekman/accessible-astro-starter/issues)
2. [Submitting a pull request](https://github.com/markteekman/accessible-astro-starter/pulls)
3. [Starting a discussion](https://github.com/markteekman/accessible-astro-starter/discussions)
4. [Buying me a coffee!](https://www.buymeacoffee.com/markteekman)

## ☕ Thank you!

A big thank you to the creators of the awesome Astro static site generator and to all using this starter to make the web a bit more accessible for all people around the world :)

[![buymeacoffee-button](https://user-images.githubusercontent.com/3909046/150683481-be070424-7bb0-4dd7-a3cb-43b5605163f5.png)](https://www.buymeacoffee.com/markteekman)
