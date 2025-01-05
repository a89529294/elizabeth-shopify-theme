## How to use

To use this repository for making Shopify themes, use the following command of Shopify CLI.

```sh
shopify theme init --clone-url https://github.com/polidario/Elizabeth_Clean
```

## Connect to a Shopify store

For the first time:

```sh
shopify theme dev --store my-store
```

For subsequent times:

```sh
shopify theme dev
```

The last part is the store name or the full url to the store.
For example, go to the homepage of your store, 'https://admin.shopify.com/store/elizabeth-dev-online-store-2/', in this instance, elizabeth-dev-online-store-2 will be the name for the store.

## install tailwindcss

Make sure you are at the root directory of the project.

1. `npm install -D tailwindcss` then `npx tailwindcss init`.
2. Check `tailwind.config.js` file. To see how to configure it.
3. Create a src folder then add `tailwind.css` file inside it.
4. Check `src/tailwind.css` file. To see how to configure it.
5. run `npx tailwindcss -i ./src/tailwind.css -o ./assets/application.css --watch`

## Add .shopifyignore

Check `.shopifyignore` file. You pretty much add everything that you added with `npm i -D tailwindcss`.
