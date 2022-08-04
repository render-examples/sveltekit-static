# sveltekit-static

This repo contains code for a SvelteKit static site generated using the [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte) package.

To create your own SvelteKit project, you can either

- [Create your own repo from this template](https://github.com/render-examples/sveltekit-static/generate) and modify it for your needs
- Create a new SvelteKit project by following the [SvelteKit Getting Started Guide](https://kit.svelte.dev/docs) and then making a few small modifications ([install `@sveltejs/adapter-static`](https://github.com/render-examples/sveltekit-static/commit/edee3add163fc00c76ac81be8c11cd9cb34ceb93), [configure `render.yaml`](https://github.com/render-examples/sveltekit-static/commit/87c806c95800847c059d03a466180800e8b843bc)) to deploy it to Render as a Static Site.

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

```bash
npm run build
```

> You can preview the built app with `npm run preview`. This should _not_ be used to serve your app in production.

## Deploying to Render

Follow the deploy instructions at https://render.com/docs/deploy-sveltekit

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/render-examples/sveltekit-static)
