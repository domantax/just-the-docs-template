# Website using just-the-docs-template

## Custom implementation of protected pages

Created new layout `protected.html` that lets you password protect specific pages. HTML needs to be run through https://robinmoisson.github.io/staticrypt/ - > salt and encrypted_msg should be added to .md file as params


## Building and previewing your site locally

Assuming [Jekyll] and [Bundler] are installed on your computer:

1.  Change your working directory to the root directory of your site.

2.  Run `bundle install`.

3.  Run `bundle exec jekyll serve` to build your site and preview it at `localhost:4000`.

    The built site is stored in the directory `_site`.
