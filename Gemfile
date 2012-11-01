source 'http://rubygems.org'

#gem 'bson', '1.3.2'
gem 'rails', '3.2.2'
gem 'jquery-rails'
gem 'rake'
#gem 'quality-measure-engine', :git => 'https://github.com/pophealth/quality-measure-engine.git', :branch => 'qme2.0' 
gem 'quality-measure-engine', '~> 2.0.0'
#gem 'quality-measure-engine', :path => '../shared/quality-measure-engine'
#gem 'health-data-standards', :git => 'https://github.com/projectcypress/health-data-standards.git', :branch => 'develop'
gem 'health-data-standards', '~> 2.1.1'
#gem 'health-data-standards', path: '../shared/health-data-standards'
#gem 'hqmf-parser', :git => 'https://github.com/pophealth/hqmf-parser.git', :branch => 'develop'
gem 'hqmf-parser', ' ~> 1.0.0'

#gem 'hqmf-parser', path: '../hqmf-parser'
#gem 'test-patient-generator', :git => 'https://github.com/pophealth/test-patient-generator.git', :branch => 'develop'
gem 'test-patient-generator', '~> 1.0.0'
#gem 'test-patient-generator', :path => '../pophealth/test-patient-generator'

gem 'state_machine'

gem 'devise', '~> 2.0'
gem 'simple_form'

gem 'prawn'
gem "prawnto_2", :require => "prawnto"
gem 'prawn_rails'
gem  "pdf-reader", '0.9.0'


gem 'thin'

gem 'pry'
gem 'pry-debugger'


gem 'mongoid-grid_fs', '~> 1.3.3' #:git=>'https://github.com/ahoward/mongoid-grid_fs.git'

# Windows doesn't have syslog, so need a gem to log to EventLog instead
gem 'win32-eventlog', :platforms => [:mswin, :mingw]

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

group :test, :develop do
  gem 'turn', :require => false
  gem 'minitest'
  gem "tailor"
  gem 'simplecov', :require => false
  gem 'mocha', :require => false
end

group :production do
  gem 'therubyracer', :platforms => [:ruby, :jruby]
end

