source 'https://rubygems.org'

# ruby '1.9.3'

gem 'locomotivecms_wagon'

group :development do
  # Mac OS X
  gem 'rb-fsevent', '~> 0.9.1', require: RUBY_PLATFORM.include?('darwin') && 'rb-fsevent'

  # Unix
  gem 'therubyracer', require: 'v8', platforms: :ruby
  gem 'rb-inotify', '~> 0.9', require: RUBY_PLATFORM.include?('linux') && 'rb-inotify'
   gem 'custom_fields', github: 'locomotivecms/custom_fields', ref: 'b5dcac5'

  # gem 'locomotivecms_steam', path: '../gems/steam', require: false
  gem 'locomotivecms_steam', github: 'locomotivecms/steam', ref: '9c95e13', require: false
  
  # Windows
  gem 'wdm', '>= 0.1.0', require: RUBY_PLATFORM =~ /mswin|mingw/i && 'wdm'
end

group :misc do
  # Add your extra gems here
  # gem 'susy', require: 'susy'
  # gem 'redcarpet', require: 'redcarpet'
end