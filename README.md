# lexisuite

A web app for smart legal document management and automation.

This project is deployed on GitHub Pages.

Access the live site: [https://igor-kan.github.io/lexisuite/](https://igor-kan.github.io/lexisuite/)

## Features
- Document creation, editing, and management
- Smart search and tagging
- Collaboration tools
- Analytics and reporting

## Technologies
- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## Local Development

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/igor-kan/lexisuite.git
    cd lexisuite
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start the development server:**
    ```bash
    npm run dev
    ```
    Open your browser to the address indicated by the dev server (usually `http://localhost:5173` or similar for Vite).

## Deployment

This app is automatically deployed to GitHub Pages from the `main` branch using GitHub Actions. The static site is built with Vite (output to the `dist` directory) and deployed.

You can also deploy manually using the `gh-pages` package if needed:
```bash
npm run deploy
```
