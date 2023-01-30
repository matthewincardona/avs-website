# AVS-website
The website for the open source Autonomous Vehicle Security project. Built with Jekyll, Tailwind, and :heart:.

## Development
Run the server with live reload enabled to make sure Tailwind regenerates static files:
<br>
`bundle exec jekyll serve --livereload
`

If you're developing on a Mac, you might run into a GitHub actions error when deploying the site, along the lines of:
'
Error: Error: The process '/opt/hostedtoolcache/Ruby/[RUBY_VERSION]/x64/bin/bundle' failed with exit code 16
'
To fix this, run
'bundle lock --add-platform x86_64-linux
'
