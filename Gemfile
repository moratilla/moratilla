source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem "google-protobuf", "~> 3.20"

# I'm using this hidejack theme
gem "jekyll-theme-hydejack", "~> 9.2.1"

# Test links and HTML validity
gem "html-proofer"
gem "nokogiri", "~> 1.18"

# If you have any plugins, put them here!
gem "rake"
gem "csv"
gem "logger"

group :jekyll_plugins do
  gem "jekyll-default-layout"
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-twitter-plugin"
  gem "jekyll-youtube"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 2.0.4"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
gem "classifier-reborn"
