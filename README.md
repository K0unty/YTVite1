https://github.com/K0unty/YTVite1/assets/119057948/ba5f9dcd-bba7-4fca-89e0-be9e7a882a3c

<h1 align="center"> <i>YTvite1</i> </h1>
<h2 align="center"><code>YTVite Tutorial</code></h2>

1. [YTVite1](#ytvite1)
   1. [Main Link](#main-link)
   2. [ViteOfficial Docs](#viteofficial-docs)
2. [With bun](#with-bun)
3. [Dirs](#dirs)
4. [Commands](#commands)
   1. [Start Vite Project - Using Bun](#start-vite-project---using-bun)
   2. [Using Vite-Inspect Plugin](#using-vite-inspect-plugin)
5. [ExternalLibs](#externallibs)
   1. [`Collect.JS`](#collectjs)
   2. [`TailwindCSS for Vite Using VUE`](#tailwindcss-for-vite-using-vue)
   3. [`SASS`](#sass)

# YTVite1

[`https://youtu.be/9oqu9134U8Q?si=nlIFAH5gbaEoNVNV `](https://youtu.be/9oqu9134U8Q?si=nlIFAH5gbaEoNVNV)

- main link

## Main Link

> Work is done here with the follows

## ViteOfficial Docs

[`https://vitejs.dev`](https://vitejs.dev)

# With bun

Bun install

```sh
curl -fsSL https://bun.sh/install | bash
```

# Dirs

1. [`W1`](./W1/) - Version 1 of the work

# Commands

## Start Vite Project - Using Bun

```sh
bun create vite
```

## Using Vite-Inspect Plugin

Third party plugin, for viewing changes and debugging in the browser.

[`https://github.com/antfu-collective/vite-plugin-inspect`](https://github.com/antfu-collective/vite-plugin-inspect)

1. This has to be manually installed in the project.
2. Official docs suggest using npm , you will use bun instead

```sh
bun i -D vite-plugin-inspect
```

3. After installing run
   `bun run dev`

4. Open browser and go to
   `http://localhost:3000/__inspect/ `

- TO access the plugin.

# ExternalLibs

> External libs being used in tutorial

## [`Collect.JS`](https://collect.js.org/)

1. Lib for working with Arrays and objects

Install

```sh
bun insall collect.js --save
```

## [`TailwindCSS for Vite Using VUE`](https://tailwindcss.com/docs/guides/vite#vue)

1. One part of the tut was focusing on hiw vite transforms _postcss_ for this , we install tailwindcss

```sh
# Installing Tailwind
bun install -D tailwindcss postcss autoprefixer

# Generating the config
bunx tailwindcss init -p
```

## [`SASS`](https://sass-lang.com/)

1.Installation code

```sh
bun i -g sass

# This is an important step
bun add -D sass
```
