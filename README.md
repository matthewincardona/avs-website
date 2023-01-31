# AVS-website
The website for the open source Autonomous Vehicle Security project. Built with Jekyll, Tailwind, and :heart:.

## Local Development
This project doesn't work with the GitHub pages version of Jekyll when running locally. Instead, un-comment the regular Jekyll version in the Gemfile and comment out the GitHub pages version. It should look similar to this:
```
gem "jekyll", "~> 4.3"

# gem "github-pages", "~> 227", group: :jekyll_plugins
```

Run the server with live reload enabled to make sure Tailwind regenerates static files:
<br>
`bundle exec jekyll serve --livereload
` 

If you run into this GitHub actions error when deploying the site
`
Error: The process '/opt/hostedtoolcache/Ruby/[RUBY_VERSION]/x64/bin/bundle' failed with exit code 16
`.
try adding Linux support to your Gemfile by locally running
`
bundle lock --add-platform x86_64-linux
`.
