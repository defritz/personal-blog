[![Netlify Status](https://api.netlify.com/api/v1/badges/85e27e8c-d042-46b2-80e8-eb79eac221a0/deploy-status)](https://app.netlify.com/sites/derek-fritz/deploys)

# Derek's Personal Blog

**A JAMstack webpage built using Hugo**

## Tech Stack
This webpage was built using victor-hugo, which is a templating tool for Hugo-based webpages. It comes with built-in support for the following tools:
- CSS transformation using PostCSS
- JS compilation/transpilation using Babel
- Asset bundling using Webpack

## Development
Local development can be performed by changing the baseurl in config.toml to "/" and deploying by running *npm start*.

New posts added to /site/content/post will be automatically picked up by the post-summary.html template.
