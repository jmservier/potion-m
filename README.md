# Potion Magique

A small potion brewing game built with **Next.js** and **TypeScript**. It features an in-memory database and a few interactive pages for brewing and managing ingredients.

## Setup

1. Install Node.js 20 or later.
2. Install dependencies:

```bash
pnpm install
```

`npm install` works as well if you prefer npm.

3. Create a `.env.local` file for environment variables. No variables are required by default, but you can define any `NEXT_PUBLIC_*` or server-side variables you might need.

## Development

Start the development server with:

```bash
pnpm dev
```

Visit `http://localhost:3000` to view the app. Hot reload is enabled.

To build for production run:

```bash
pnpm build
pnpm start
```

## Testing

Run the Jest test suite with:

```bash
pnpm test
```

For coverage information:

```bash
pnpm run test:coverage
```

Linting can be run with `pnpm run lint` and auto-fixed using `pnpm run lint -- --fix`.

## Project Structure

See `AGENTS.md` for a detailed directory overview. Main folders include `src/app` for Next.js routes, `src/lib` for utilities and the in-memory database, and `src/components` for React components.

