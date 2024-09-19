### This project is created and intended to be used for the [Shopify Theme Development – Online Store 2.0 + TailwindCSS]

## How to use

If you want to start from scratch, then following cammand will create an empty theme

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
