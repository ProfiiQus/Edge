## Note

This is a forked, slightly edited version of Ghost Edge Theme. I made a few changes for my friend, so that he can have the finest [personal page](https://antoninkrejci.com/) possible. This theme is also being automatically uploaded to the website via GitHub Actions!

# Edge

A visually aesthetic theme designed for creative professionals. Showcase your works with minimal style and presentation. Completely free and fully responsive, released under the MIT license.

**Demo: https://edge.ghost.io**

&nbsp;

# Instructions

1. [Download this theme](https://github.com/TryGhost/Edge/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
yarn zip
```

# PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.

# Copyright & License

Copyright (c) 2013-2022 Ghost Foundation - Released under the [MIT license](LICENSE).
