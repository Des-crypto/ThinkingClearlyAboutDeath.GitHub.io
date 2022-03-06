source 'https://rubygems.org'
#gem 'github-pages', group: :jekyll_plugins
#gem 'jekyll-admin', group: :jekyll_plugins
gem "jekyll", "~> 4.2.2"
gem "jemoji", "~> 0.12.0"
gem "jekyll-sitemap", "~> 1.4.0"
#gem "jekyll-feed", "~> 0.16.0"
gem "jekyll-paginate","~>1.1.0"
#gem "jekyll-gist","~>1.5.0"
group :jekyll_plugins do
   gem "jekyll-gist"
 end

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.7"

gem 'jekyll-swiss', '~> 1.0'
gem 'jekyll-theme-persephone', '~> 0.3.3'
