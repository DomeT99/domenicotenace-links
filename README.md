# Domenico Tenace Links

A simple personal link-in-bio website built with Astro. It showcases profile information, social links, and quick access buttons to websites, projects, and contact channels.

## Features

- Clean, minimalist landing page
- Profile header with bio and social links
- Custom link buttons for portfolio, blog, support, and contact
- SEO metadata and social sharing tags

## Project Structure

```text
src/
  components/     # Reusable Astro components
  data/           # Profile and link content (JSON)
  pages/          # Main page entry
  styles/         # Global styles
public/           # Static assets such as images and favicons
```

## Development

Install dependencies:

```bash
pnpm install
```

Start the local development server:

```bash
pnpm dev
```

Build for production:

```bash
pnpm build
```

Preview the production build:

```bash
pnpm preview
```

## Content Customization

You can update the site content by editing:

- `src/data/profile.json` for profile details and socials
- `src/data/links.json` for the main buttons
