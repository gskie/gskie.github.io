source "https://rubygems.org"
ruby RUBY_VERSION

# We'll need rake to build our site in TravisCI
gem "rake", "~> 12"
gem "jekyll"

#gem "github-pages", group: :jekyll_plugins

# Optional: Add any custom plugins here.
# Some useful examples are listed below
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem 'jekyll-paginate'
  gem "jekyll-paginate-v2"
  gem "jekyll-seo-tag"
  gem "jekyll-compose", "~> 0.5"
  gem "jekyll-redirect-from"
  gem 'jekyll-timeago'
  gem 'jekyll-archives'
  gem 'jekyll-tagging'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'wdm', '~> 0.1.1', :install_if => Gem.win_platform?