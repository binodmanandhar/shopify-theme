### This project is created and intended to be used for the [Shopify Theme Development – Online Store 2.0 + TailwindCSS]

## How to use

If you want to start from scratch, then following cammand will create an empty theme

```sh
shopify theme init [ NAME OF YOUR THEME ] --clone-url https://github.com/polidario/Elizabeth_Clean
```

If you don't have Shopify CLI installed to your computer, navigate to the [installation page of Shopify CLI](https://shopify.dev/themes/tools/cli/installation).

### Few setup before running

#### create a folder call _src_ in root directory and create a file as tailwind.css

Add following files

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

#### Add node modules

```
npm install
```

#### Running theme CLI command in local

```
shopify theme dev
```

##### It opens with http://127.0.0.1:9292

```
npx tailwindcss -i ./src/tailwind.css -o ./assets/application.css --watch
```

#### How to go to theme preview

```https://admin.shopify.com/store/[storename]/themes/[theme_preview_id]/editor

```

```
https://admin.shopify.com/store/binodstore/themes/133817925692/editor
```
