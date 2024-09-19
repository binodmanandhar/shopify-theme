### This project is created and intended to be used for the [Shopify Theme Development – Online Store 2.0 + TailwindCSS course]

## How to use

Use this repository for making Shopify themes, use the following command of Shopify CLI.

```sh
shopify theme init [ NAME OF YOUR THEME ] --clone-url https://github.com/polidario/Elizabeth_Clean
```

If you don't have Shopify CLI installed to your computer, navigate to the [installation page of Shopify CLI](https://shopify.dev/themes/tools/cli/installation).

### Few setup before running

#### create a folder call _src_ in root directory

Add following files

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

#### Running theme CLI command in local

```
shopify theme dev
```

```
npx tailwindcss -i ./src/tailwind.css -o ./assets/application.css - - watch
```
