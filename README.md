# Dawnx

A Ghost theme based on the original Dawn theme with a few tweaks and enhancements.

**Demo: https://kawaijoe.com**

# Instructions

1. [Download this theme](https://github.com/kawaijoe/dawnx/releases)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file
3. Go to `Advanced` settings area and upload the `redirects.yaml` and `routes.yaml` files under Labs (Beta features).

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [PNPM](https://pnpm.io/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
pnpm install

# Run build & watch for changes
pnpm run dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/dawn.zip`, which you can then upload to your site.

```bash
pnpm run zip
```
