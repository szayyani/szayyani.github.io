# frozen_string_literal: true

source "https://rubygems.org"
gem "jekyll", "~> 4.3.3"
gem "jekyll-theme-chirpy", "~> 7.0", ">= 7.0.1"

group :test do
  gem "html-proofer", "~> 5.0"
end

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-default-layout'
  gem 'jekyll-spaceship'
  gem 'jekyll-tagging-related_posts'
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end


# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
