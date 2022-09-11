# Hugo Starter Theme

Dead-simple Hugo theme with everything you need to get started. Intended to be a starter for creating your own theme without including useless bloat like most Hugo themes.

This is a template fork of the [Hugo starter theme by ericmurphyxyz](https://github.com/ericmurphyxyz/hugo-starter-theme).

## Getting started

This repo is set to be a template, which means you can create your own repo from this on Github.
If you would like to do this from the command line interface, then run:
```bash
gh repo create <new-repo-name> --template=skullbunnygalaxy/hugo-starter-theme
```

Alternatively, copy and remove the git history with [`degit`](https://github.com/Rich-Harris/degit) in one step:

```bash
npx degit https://github.com/skullbunnygalaxy/hugo-starter-theme themes/<your-theme-name>
```

If you'd like some example content and an example config file to get started, you can copy the `exampleSite` directory into your root Hugo directory.

```bash
cp -r themes/your-theme-name/exampleSite/* ./
```

To learn more about building themes in Hugo, refer to Hugo's [templating documentation](https://gohugo.io/templates/).

