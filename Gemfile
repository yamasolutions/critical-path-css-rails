source 'https://rubygems.org'

gemspec

group :development, :test do
  gem 'actionpack'
  gem 'byebug', platform: [:ruby], require: false
  gem 'rubocop', require: false
  gem 'rspec-rails', '~> 3.8'
  gem 'capybara', '~> 3.14'
  gem 'pry-rails'
end

# # HACK: npm install on bundle
# unless $npm_commands_hook_installed # rubocop:disable Style/GlobalVars
#   Gem.pre_install do |installer|
#     next true unless installer.spec.name == 'critical-path-css-rails'
#     require_relative './ext/npm/install'
#   end
#   $npm_commands_hook_installed = true # rubocop:disable Style/GlobalVars
# end
