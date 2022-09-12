# DaisyWindGo Starter Theme

DaisyWindGo is a starter theme that utilizies TailwindCSS v3 + Daisyui.

Based on a template fork of the [Hugo starter theme by ericmurphyxyz](https://github.com/ericmurphyxyz/hugo-starter-theme).

## Getting started

This repo is set to be a template, which means you can create your own stand-alone repo from this on Github.
If you would like to do this from the command line interface, then run:

```bash
gh repo create <new-repo-name> -p skullbunnygalaxy/hugo-starter-theme --public
```

Note: `--public` can be replaced by `--private` or `--internal`

Alternatively, copy and remove the git history with [`degit`](https://github.com/Rich-Harris/degit) in one step:

```bash
npx degit https://github.com/skullbunnygalaxy/hugo-starter-theme themes/<your-theme-name>
```

If you'd like some example content and an example config file to get started, you can copy the `exampleSite` directory into your root Hugo directory.

```bash
cp -r exampleSite/* ./
```

To learn more about building themes in Hugo, refer to Hugo's [templating documentation](https://gohugo.io/templates/).

## NPM Dependencies
├── daisyui@2.27.0
├── npm-run-all@4.1.5
└── tailwindcss@3.1.8

## Commands
- `npm run dev`
- `npm run build`
- `serve public`
