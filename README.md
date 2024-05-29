# A Svelte Template for Interactive Articles with Svelte

For UCSD dataviz course: [https://dsc106.com/](https://dsc106.com/).

This is a starter template to build an interactive article using Svelte.

It comes with some built-in features:

- Responsiveness
- Support for browser-rendered math equations
- Scrollytelling built-in
- An example of a responsive, d3 + svelte visualization.

### Getting Started

To get started, first clone this repository. Then:

```
# install dependencies
npm istall
```

Then run development version:

```
npm run dev
```

To build for prod:

```
npm run build
```

### Deploying to GitHub Pages

The easiest way it to bundle the assets, then upload this to your github pages repo (or the `gh-page` branch).

First, create the `dist/` dir:

```
npm run build
```

Then, copy the contents of this `dist/` to your `__.github.io` git repo. E.g.;

```
cp -r dist/* ../path/to/your-website.github.io
```

### Deploying to GitHub Pages CI

Follow the steps in this README: [https://github.com/sitek94/vite-deploy-demo](https://github.com/sitek94/vite-deploy-demo).

Note that this is a Vite repo, so you may start at the header titled, "**Create a new GitHub repository**":
