source "https://rubygems.org"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

gem "jekyll"
gem "jekyll-sitemap"
gem "jekyll-gist"
gem "jekyll-feed"
gem "jekyll-paginate"
# gem 'github-pages', group: :jekyll_plugins
