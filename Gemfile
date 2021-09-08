source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 6.0.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'


gem 'bootsnap', '>= 1.4.2', require: false

# added gems for this project   ******************************************
gem 'bulma-rails', '~> 0.7.5'     # CSS
gem 'simple_form', '~> 4.1'
#gem 'gravatar_image_tag', '~> 1.2'
gem 'devise', '~> 4.7'
#gem 'jquery-rails', '~> 4.3', '>= 4.3.1'
#gem "wysiwyg-rails"
#gem 'public_activity', '~> 1.5'

#  ***********************************************************************

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors', '~> 2.8'
  gem "binding_of_caller"
  gem 'guard', '~> 2.15'                                           
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2', require: false  
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]