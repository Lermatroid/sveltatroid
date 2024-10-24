# Sveltatroid

This is a template for a Svelte 5 app using the following technologies:

- Svlete / Svelte Kit
- Drizzle w/ Turso
- Lucia Auth
- Tailwind CSS
- Prettier
- Pnpm

You probably don't want to use this! Generally CLI based things are better as they let you pick what you need and what you don't with ease. Certainly look into something like [Create o7 App](https://github.com/ottomated/create-o7-app)!

## Creating a project

tbd

## Developing

Once you've created a project and installed dependencies with `pnpm install`, start a development server:

```bash
pnpm run dev

# or start the server and open the app in a new browser tab
pnpm run dev -- --open
```

## Building

To create a production version of your app:

```bash
pnpm run build
```

You can preview the production build with `pnpm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
