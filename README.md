# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.


Install picocss to style stuff for small projects:

```
pnpm i @picocss/pico
```

Intialize prisma setup with the following:

```
npx prisma init
```

Add the database changes and models in the `prisma/schema.prisma` file.

Once that is done, for the first time, you'll want to push the objects to the new database. In prod, use migrations.

```
npx prisma db push
```

Install this sqlviewer extension to see the database inside vscode:

```
Name: SQLite Viewer
Id: qwtel.sqlite-viewer
Description: SQLite Viewer for VSCode
Version: 0.3.13
Publisher: Florian Klampfer
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=qwtel.sqlite-viewer
```


