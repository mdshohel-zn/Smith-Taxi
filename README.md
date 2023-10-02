# Smith Taxi website

[![Netlify Status](https://api.netlify.com/api/v1/badges/013fcf60-7621-476d-8709-bfc4767b737b/deploy-status)](https://app.netlify.com/sites/smithtaxi/deploys)

This website is built using [Jekyll](https://jekyllrb.com/). As such, the HTML files in this repository are built using the [liquid templating language](https://shopify.github.io/liquid/basics/introduction/).

## Install

Requires ruby 2.7

```bash
git clone https://github.com/pontikos-lab/lab_website
cd lab_website
bundle install
```

Then you can test what the web site looks like. Run:

```bash
bundle exec jekyll serve --incremental --watch
```

This will rebuild the pages (into `_site`) every time you save a change, and serve them on a local http server (e.g. http://127.0.0.1:4000).

## Deployment

Deployment is handled by Netlify.

Any code pushed to the master branch will be automatically built (using jekyll) and deployed.
