source 'https://rubygems.org'

gem 'jekyll', '~> 4.2.0'
gem 'bundler', '~> 2.2.0'
gem 'minima', '~> 2.5'

group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.15'
  gem 'jekyll-seo-tag', '~> 2.8'
end

group :test do
  gem 'html-proofer', '~> 3.19'
end

# Windows and JRuby does not include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '~> 1.2'
  gem 'tzinfo-data'
end

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1.1', :platforms => [:mingw, :x64_mingw, :mswin]