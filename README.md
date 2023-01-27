# AVS-website
A lovely little Jekyll & Tailwind website.

## Development
Note: The GitHub pages gem doesn't work with Jekyll & Tailwind. Before starting, you'll have to edit the Gemfile by commenting out the GitHub pages plugin and un-commenting the line for regular Jekyll. It should look like this:

```
gem "jekyll", "~> 4.3"
<br>
# gem "github-pages", "~> 227", group: :jekyll_plugins
```

And to make sure Tailwind regenerates static files, run the server with live reload enabled:
<br>
`bundle exec jekyll serve --livereload
`

Double note: to avoid any issues, the Gemfile is currently ignored and not updated when pushing.
