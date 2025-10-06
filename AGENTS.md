# Repository Guidelines

## Project Structure & Module Organization

- **Root HTML**: `index.html`, `game_blue.html`, `game_grey.html`, `game_pink.html`, `news.html`, etc.
- **`css/`**: Core styles (`index.css`), variable definitions (`variables.css`), theme sheets, and component-specific CSS.
- **`components/`**: Reusable HTML fragments (navbar, footer, hero, product grid).
- **`images/`**: Logos and cartridge poster assets.
- **`buying-page/`**: Purchase flow HTML for each cartridge theme.
- **`news/`**: Community news articles and assets.

## Build, Test, and Development Commands

- **Serve locally**: `python3 -m http.server` (root) or open `index.html` directly.
- **Install dependencies**: No build tools; static HTML/CSS only.
- **Run tests**: `npm test` (placeholder – no automated tests configured).

## Coding Style & Naming Conventions

- **Indentation**: 4 spaces in HTML and CSS.
- **Naming**: lowercase, hyphen-separated for files, classes, and IDs (e.g., `product-card`).
- **CSS Variables**: Defined in `css/variables.css`; use `var(--primary-color)` in styles.
- **HTML**: lowercase tags and attributes; avoid inline styles unless necessary.

## Testing Guidelines

- No automated suite; perform manual QA in Chrome, Firefox, and Safari.
- Check responsive layout via browser dev tools (mobile and desktop breakpoints).

## Commit & Pull Request Guidelines

- **Commit messages**: follow Conventional Commits (`feat:`, `fix:`, `chore:`, etc.).
- **PR descriptions**: concise summary, linked issue (if any), and context for changes.
- **UI changes**: include before/after screenshots or GIFs.

