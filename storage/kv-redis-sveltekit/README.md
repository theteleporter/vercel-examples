---
name: Redis SvelteKit Starter
slug: kv-redis-sveltekit
description: Simple SvelteKit template that uses Redis to track pageviews.
framework: Svelte
useCase: Starter
css: Tailwind
database: Redis
deployUrl: https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fexamples%2Ftree%2Fmain%2Fstorage%2Fkv-redis-sveltekit&project-name=kv-redis-sveltekit&repository-name=kv-redis-sveltekit&demo-title=Vercel%20KV%20for%20Redis%20SvelteKit%20Starter&demo-description=Simple%20Svelte%20template%20that%20uses%20Vercel%20KV%20for%20Redis%20to%20track%20pageviews.&demo-url=https%3A%2F%2Fkv-redis-sveltekit.vercel.app%2F&demo-image=https%3A%2F%2Fkv-redis-sveltekit.vercel.app%2Fopengraph-image.png&products=%5B%7B"type"%3A"integration"%2C"group"%3A"redis"%7D%5D
demoUrl: https://kv-redis-sveltekit.vercel.app/
relatedTemplates:
  - blob-starter
  - postgres-starter
---

# Redis SvelteKit Starter

Simple SvelteKit template that uses Redis to track pageviews.

## Demo

https://kv-redis-sveltekit.vercel.app/

## How to Use

You can choose from one of the following two methods to use this repository:

### One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fexamples%2Ftree%2Fmain%2Fstorage%2Fkv-redis-sveltekit&project-name=kv-redis-sveltekit&repository-name=kv-redis-sveltekit&demo-title=Vercel%20KV%20for%20Redis%20Svelte%20Starter&demo-description=Simple%20SvelteKit%20template%20that%20uses%20Vercel%20KV%20for%20Redis%20to%20track%20pageviews.&demo-url=https%3A%2F%2Fkv-redis-sveltekit.vercel.app%2F&demo-image=https%3A%2F%2Fkv-redis-sveltekit.vercel.app%2Fopengraph-image.png&products=%5B%7B"type"%3A"integration"%2C"group"%3A"redis"%7D%5D)

### Clone and Deploy

Execute the following command to download the example into the `my-project` folder:

```bash
npx degit@latest https://github.com/vercel/examples/storage/kv-redis-sveltekit my-project
```

Once you've created the project and installed dependencies with `pnpm install`, copy the `.env.example` file in this directory to `.env.local` (which will be ignored by Git). Then open `.env.local` and set the environment variables to match the ones in your Vercel Storage Dashboard.

Alternatively, if you have setup a project already and you have installed the Vercel CLI, you can also pull the environment variables using the following command:

```bash
vercel env pull .env.local
```

Next, run SvelteKit in development mode:

```bash
pnpm dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples) ([Documentation](https://vercel.com/docs/frameworks/sveltekit)).
