source 'https://rubygems.org'

ruby File.read('.ruby-version').strip

gem 'rails', '~> 5.2.0'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'responders'
gem 'simple_form'
gem 'rack-canonical-host'
gem 'bootsnap'

# Asset related
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'bootstrap-sass', '~> 3.4.1'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem "rspec-rails"
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  # Preview emails in development
  gem 'letter_opener'
end

group :test do
  gem "capybara"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "mimemagic", git: "https://github.com/minad/mimemagic.git", ref: "01f92d86d15d85cfd0f20dabd025dcbd36a8a60f"
