source 'https://rubygems.org'

ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# gem 'rails', '>= 5.0.0.beta1.1', '< 5.1'
gem 'rails', '5.0.0.1'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.4'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~> 2.7.2'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.1.1'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby
# Use haml
gem 'haml', '~> 4.0.7'
gem 'less-rails', '~> 2.7.1'
gem 'therubyracer', '~> 0.12.2'

# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 4.2.1'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.4.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.1',          group: :doc
#gem 'foundation-rails', '5.4.3.1'
gem 'twitter-bootstrap-rails', :git => 'git://github.com/seyhunak/twitter-bootstrap-rails.git'
gem 'font-awesome-rails'
gem 'simple_form', '~> 3.2.1'

gem 'awesome_print', git: 'https://github.com/awesome-print/awesome_print'
gem 'devise', '~> 4.0'
gem 'will_paginate', '~> 3.1.0'
gem 'cancancan', '~> 1.13.1'
gem 'secure_headers', '~> 2.5.0'
gem 'autoprefixer-rails', '~> 6.3.1'

# Comment/Uncomment depending on what database your going to use
#gem 'mysql2'
gem 'pg', '~> 0.18.2'

group :development do
  gem 'guard', '~> 2.13.0'
  gem 'haml-rails', '~> 0.9.0' # only in dev, because haml-rails adds the generators
  gem 'rails_layout'
  gem 'bullet', '~> 5.0.0'
  gem 'meta_request'
  gem 'shog', '~> 0.1.8'
  # For supporting flamegraph without errors
  # see here: https://github.com/SamSaffron/flamegraph/blob/master/lib/flamegraph.rb#L5
  gem 'stackprof', '~> 0.2.8'
  gem 'rack-mini-profiler', '~> 0.9.8', require: false
  gem 'flamegraph', '~> 0.1.0'
  # gems for inspecting code qualitty
  gem 'i18n-tasks', '~> 0.9.2'
  gem 'rails_best_practices', '~> 1.15.7', require: false
  gem 'inch', '~> 0.7.0', require: false
  gem 'guard-inch', '~> 0.2.0'
  gem 'rubocop', '~> 0.36.0', require: false
  gem 'guard-rubocop', '~> 1.2.0'
  gem 'rubycritic', '~> 2.7.0', require: false
  # remove guard-rubycritic in favour of using the new version of rubycritic
  # gem 'guard-rubycritic', '~> 1.4.0'
  gem 'brakeman-min', '~> 3.1.5', require: false
end

group :development, :test do
  gem 'jazz_hands', github: 'vwall/jazz_hands'
  # If you use gems that require environment variables to be set before they are loaded,
  # then list dotenv-rails in the Gemfile before those other gems and require dotenv/rails-now.
  # gem 'dotenv-rails', :require => 'dotenv/rails-now'
  # gem 'gem-that-requires-env-variables'
  gem 'dotenv-rails', '~> 2.1.0'
end

group :test do
  gem 'simplecov', '~> 0.11.1'
  gem 'simplecov-html', '~> 0.10.0'
  gem 'vcr', '~> 3.0.1'
  gem 'webmock', '~> 1.22.6'
  gem 'faker', '~> 1.6.1'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'rspec-rails', '~> 3.5'
  gem 'rspec-support', '~> 3.5.0'
  gem 'capybara', '~> 2.6.2'
  gem 'launchy', '~> 2.4.3'
  gem 'shoulda-matchers', '~> 3.1.1'
  gem 'poltergeist', '~> 1.8.1'
  gem 'capybara-screenshot', '~> 1.0.11'
  gem 'database_cleaner', '~> 1.5.1'
  gem 'ammeter', '~> 1.1.3'
end

group :production do
  gem 'rails_12factor'
  gem 'newrelic_rpm', '~> 3.14.2.312'
  gem 'unicorn', '~> 5.0.1'
end
