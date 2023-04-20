# vite-plugin-ssr issue with vite-plugin-cloudflare

When running `npm run dev` and accessinh `/`, the page renders:

> could not find index.html in your content namespace

And the console output is:

```
Error: [vite-plugin-ssr@0.4.18][Wrong Usage] Cannot find production build. Did you to run `$ vite build`? If you did, then you may need to use `importBuild.cjs`, see https://vite-plugin-ssr.com/importBuild.cjs
```
