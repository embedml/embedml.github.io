# embedml website

[![workflow](https://github.com/embedml/embedml.github.io/actions/workflows/gh-pages.yml/badge.svg)](https://github.com/embedml/embedml.github.io/actions/workflows/gh-pages.yml)

Website to showcase our projects and resources

## Contribute

Clone this repository

```bash
git clone https://github.com/embedml/embedml.github.io.git
```

Install [Hugo](https://gohugo.io/getting-started/installing) for your OS

Run server on your machine

```bash
hugo server -D
```

Build static files

```bash
hugo -D
```

## Deployment

Github pages is used to host the website. Any push to 'main' branch will trigger the workflow in order to deploy via Github Pages. You can run this workflow [manually](https://github.com/embedml/embedml.github.io/actions/workflows/gh-pages.yml) if needed.

The final minified files and other assets used for the website are in the 'gh-pages' branch. As such, the gh-pages branch must be selected as the source for Github Pages found in the settings of this repository.
