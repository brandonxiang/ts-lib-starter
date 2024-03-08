# Awesome Starter

## Why do you use this template

If you’re looking to transpile your TypeScript code into ESM code for your codebase, you can use the starter template to initialize your project.

This will help you get started quickly and easily with your project by providing you with a pre-configured environment that includes all the necessary tools and dependencies for building and running your TypeScript code as ESM modules. Additionally, the starter template provides you with a set of best practices and guidelines for structuring your codebase in a way that’s easy to maintain and scale as your project grows.

Because moduleResolution needs to be nodenext, relative import paths require explicit file extensions in EcmaScript imports

## What is the key web framework for this template

- [typeScript](https://www.typescriptlang.org/)

## Start Up

Please use [degit](https://github.com/Rich-Harris/degit) to download template

```bash
mkdir your-project-name
cd your-project-name
npx degit brandonxiang/ts-lib-starter

# or

npx degit brandonxiang/ts-lib-starter your-project-name
```

## How to Develop

```shell
pnpm i
```

```shell
pnpm run dev

# http://localhost:3000/
```

## How to Build

```shell
# live
pnpm run build
```
