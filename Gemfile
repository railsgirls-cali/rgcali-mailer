source 'https://rubygems.org'

ruby '2.3.3'

gem 'rails', '4.2.10'
gem 'mongoid', '~> 5.1.0'
gem 'mail_form'
gem 'sass'
gem 'active_attr'
gem 'jquery-rails'
gem 'simple_form'
gem 'bluecloth'
gem 'haml-rails'
# gem 'pry'
gem 'pry-rails'
gem 'rb-readline', require: false
gem 'puma', '3.12.0'
gem 'materialize-sass', '0.97.7'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'mini_racer'

  gem 'uglifier', '>= 3.0.0'
end


# group :test, :development do
#   gem 'jazz_hands'
# end

group :development, :staging do
  gem 'binding_of_caller'
  gem 'quiet_assets'
end

group :test do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'spork-rails'
end

group :production do
  gem 'rails_12factor'
  #gem 'unicorn'
  gem 'rails_stdout_logging', '~> 0.0.5'
end
