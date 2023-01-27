# AVS-website
A lovely little Jekyll & Tailwind website.

## Development
Note: The GitHub pages plugin doesn't work with Jekyll & Tailwind. Before starting, you'll have to edit the Gemfile by commenting out the GitHub pages plugin and un-commenting the line for regular Jekyll. It should look like this:

`gem "jekyll", "~> 4.3"`
`# gem "github-pages", "~> 227", group: :jekyll_plugins`

And to make sure Tailwind regenerates the static files, run the server with live reload enabled:
bundle exec jekyll serve --livereload

