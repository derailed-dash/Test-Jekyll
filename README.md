# Just a Site for Testing Jekyll Stuff

- The Jekyll site is in the `docs` folder.
- I'm using `github-pages-unscramble`, in order to utilise plugins that are not in the GitHub Pages whitelist.
- The site is built and deployed using the `jekyll-deploy-action` GitHub action, rather than standard GitHub workflow for GitHub Pages.  Again, this is so that we can use plugins that aren't on the whitelist.
- Plugins are defined in the Gemfile, e.g. \
  `gem 'jekyll-spaceship'`
