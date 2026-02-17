# CV - Snaider Armando Rangel Rondon

Minimalist portfolio and CV built with [Astro](https://astro.build/), powered by a JSON file for fast and easy customization.

## Technologies

- **Astro** — Static web framework for optimal performance
- **TypeScript** — Static typing for robustness
- **Plus Jakarta Sans** — Main typography

## Project Structure

```
├── cv.json              # CV data in Spanish
├── cv_english.json      # CV data in English
├── public/              # Static files (photo, favicon)
└── src/
    ├── components/      # Reusable components
    │   └── sections/    # CV sections (Hero, About, Experience, etc.)
    ├── icons/           # SVG icons as Astro components
    ├── layouts/         # Main layout
    └── pages/           # Site pages
```

## How to use

### 1. Install dependencies

```bash
bun install
```

### 2. Start the development server

```bash
bun run dev
```

### 3. Customize

Edit the `cv.json` file with your personal information. Available fields:

- **basics** — Name, title, image, email, phone, summary, location, social profiles
- **work** — Work experience
- **education** — Academic background
- **skills** — Technical skills
- **projects** — Featured projects
- **languages** — Languages

> If a section has an empty array, it will not be rendered on the page.

### 4. Build for production

```bash
bun run build
```

### 5. Print as PDF

Use `Ctrl + P` in your browser to print or save as PDF. Margins are optimized to remove browser headers/footers.

## Keyboard Shortcuts

The portfolio includes a keyboard shortcut manager for quick navigation.

## License

[MIT](LICENSE.txt)
