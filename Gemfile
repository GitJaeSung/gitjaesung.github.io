# Ruby gem configuration
# Ruby
source "https://rubygems.org"

# Jekyll
gem "jekyll", "~> 4.2.2"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.16.0"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-paginate", "~> 1.1.0"
end

# Library
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Gem added after ruby 3.0
gem "webrick", "~> 1.7"
