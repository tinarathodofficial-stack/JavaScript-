# JavaScript Basics: History & TC39 Committee Notes

A beautifully styled, high-performance Astro project dedicated to documenting the history, evolution, and governance of JavaScript (ECMAScript). 

## 🚀 Project Overview

This repository has been customized to focus purely on the core evolution of the language:
1. **Interactive History Timeline** (`/`): A clean, vertical timeline charting 10 major milestones from JavaScript's creation in 1995 to its usage as a universal runtime today. Includes visual callouts (**Facts**, **Insights**, and **Did You Know?** alerts).
2. **About TC39 Page** (`/tc39`): A dedicated subpage introducing Technical Committee 39, its responsibilities (Standardization, Consensus, Testing/Test262, Backwards Compatibility), and the **Five-Stage standardization process** of ECMA-262.

---

## 📂 Custom Project Structure

Inside this project, you'll find:

```text
├── public/
│   └── favicon.png         # Document browser tab icon
├── src/
│   ├── layouts/
│   │   └── Layout.astro    # Common page wrapper, header navigation, and footer
│   ├── pages/
│   │   ├── index.astro     # Main homepage route (Hero & History Timeline)
│   │   └── tc39.astro      # Separate route for TC39 Committee notes (/tc39)
│   └── styles/
│       └── global.css      # Core Design System, visual tokens, and custom styling
├── astro.config.mjs        # Astro project configuration
├── package.json            # Scripts and NPM dependency registry
└── tsconfig.json           # TypeScript configuration
```

---

##  Genie Commands

All commands are run from the root of the project:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs project dependencies |
| `npm run dev` | Starts local development server at `http://localhost:4321` |
| `npm run build` | Builds the static site production bundle to `./dist/` |
| `npm run preview` | Previews the local build before deployment |

---

## 🎨 Theme & Styling

This project features a premium glassmorphic dark mode theme:
*   **Colors**: Custom CSS variables for gradients, backgrounds, borders, and callouts (Amber/Orange for facts, Indigo for insights, Emerald/Green for trivia).
*   **Fonts**: Styled using modern system sans-serif typography.
*   **Responsiveness**: Grid-based layouts that adjust automatically for desktop, tablet, and mobile views.
