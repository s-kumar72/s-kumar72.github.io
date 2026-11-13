source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'jekyll'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

gem 'github-pages'
gem 'connection_pool', '2.5.0'

# Libraries that newer Ruby versions (3.4+) no longer bundle by default.
# Needed only to run the site locally; GitHub Pages ignores this file.
gem 'csv'
gem 'base64'
gem 'bigdecimal'
gem 'logger'
gem 'ostruct'
# Liquid 4.0.3 crashes on Ruby 3.2+ ("undefined method 'tainted?'"); 4.0.4 fixes it.
gem 'liquid', '>= 4.0.4'
