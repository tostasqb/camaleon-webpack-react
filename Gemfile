source 'https://rubygems.org'

gem 'rails', '~> 5.2.1'

gem 'sqlite3', '< 1.4.0', group: :development
gem 'pg', group: [:production, :test]

gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'webpacker'
gem 'webpacker-react'
gem 'jbuilder', '~> 2.5'

gem 'camaleon_cms', '~> 2.4.5'
gem 'draper', '~> 3'

gem 'bootsnap', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

#################### Camaleon CMS include all gems for plugins and themes #################### 
require './lib/plugin_routes' 
instance_eval(PluginRoutes.draw_gems)