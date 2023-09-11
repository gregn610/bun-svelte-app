
```bash
# create a new project in the current directory
bunx create-svelte@latest
# create a new project in my-app
bunx create-svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `bun install` , start a development server:

```bash
bun run dev

# or start the server and open the app in a new browser tab
bun run dev -- --open
```

## Building

To create a production version of your app:

```bash
bun run build
```

You can preview the production build with `bun run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

```shell
bun run dev
bun install -D @sveltejs/adapter-node
bun run build
bun run build/index.js

```
