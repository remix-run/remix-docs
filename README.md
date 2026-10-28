# Remix Documentation

This repo hosts the [Remix](https://github.com/remix-run/remix) guides and API reference on GitHub Pages at [docs.remix.run](https://docs.remix.run).

The [deploy workflow](.github/workflows/deploy.yml) checks out Remix at a release tag, builds and prerenders the docs site from `docs/site`, and publishes the result with GitHub Pages. The Remix publish workflow triggers it on each release. To deploy by hand, run it from the Actions tab or with:

```sh
gh workflow run deploy.yml -R remix-run/remix-docs -f ref=remix@<version>
```

Older docs are available at their Git tags in the Remix repo.
