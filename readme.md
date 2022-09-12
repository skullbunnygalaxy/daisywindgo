# DaisyWindGo Starter Theme

DaisyWindGo is a [Hugo](https://gohugo.io/documentation/) starter theme that utilizies [TailwindCSS](https://tailwindcss.com/) v3 + [DaisyUI](https://daisyui.com/).

This theme is based on a template fork of the [Hugo starter theme by ericmurphyxyz](https://github.com/ericmurphyxyz/hugo-starter-theme).

## Getting started

This repo is set to be a template, which means you can create your own stand-alone repo from this on Github.
If you would like to do this from the command line interface, then run:

```bash
gh repo create <new-repo-name> -p skullbunnygalaxy/hugo-starter-theme --public
```

Note: `--public` can be replaced by `--private` or `--internal`
Then `git clone` normally.

Alternatively, copy and remove the git history with [`degit`](https://github.com/Rich-Harris/degit):

```bash
npx degit https://github.com/skullbunnygalaxy/hugo-starter-theme themes/<your-theme-name>
```

If you'd like some example content and an example config file to get started, you can copy the `exampleSite` directory into your root Hugo directory.

```bash
cp -r exampleSite/* ./
```

Finally install npm dependencies by running `npm install`.

To learn more about building themes in Hugo, refer to Hugo's [templating documentation](https://gohugo.io/templates/).

## NPM Dependencies
- daisyui@2.27.0
- npm-run-all@4.1.5
- tailwindcss@3.1.8
- @tailwindcss/aspect-ratio@0.4.2
- @tailwindcss/typography@0.5.7

## Commands
- `npm run dev`
- `npm run build`
- `serve public`
