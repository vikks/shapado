# Edit this Gemfile to bundle your application's dependencies.
# This preamble is the current preamble for Rails 3 apps; edit as needed.
source 'http://rubygems.org'

gem 'rails', '3.1.0'

if RUBY_PLATFORM !~ /mswin|mingw/
  gem 'rdiscount', :git => 'git://github.com/ricodigo/rdiscount.git'

  gem "ruby-stemmer", "~> 0.8.2", :require => "lingua/stemmer"
  gem "sanitize", "2.0.3"

  gem 'magic'
  gem 'mini_magick', '~> 2.3'
  gem 'nokogiri'
  gem 'mechanize'
else
  gem "maruku", "0.6.0"
end
gem "maruku" # A pure-Ruby Markdown-superset interpreter
# ui
gem "haml" #HTML Abstraction Markup Language - A Markup Haiku.
gem "sass" #Sass (Syntactically Awesome Stylesheets) is a stylesheet language
gem 'compass', '0.11.1' # Compass is a Stylesheet Authoring Environment that makes your website design simpler to implement and easier to maintain
gem "compass-colors", "0.9.0" #compass-colors - Color Tools and Theme Support for Compass and Sass.
gem "fancy-buttons", "1.1.1" #fancy-buttons - Fancy CSS Buttons using Compass
gem 'kaminari' #A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Rails 3.

# mongodb
gem 'bson', '1.4.0' #Independent BSON codec for Python that doesn't depend on MongoDB.
gem 'bson_ext', '1.4.0' #C extensions for performance boost

gem 'mongo', '1.4.0' #mongo database 
gem 'mongoid', :git => 'git://github.com/mongoid/mongoid.git', :branch => "2.3.0-stable" #Ruby ODM framework for MongoDB
gem 'mongoid_ext', :git => "git://github.com/dcu/mongoid_ext.git" #Mongoid Plugins

gem 'mongo_store', :git => 'https://github.com/Houdini/mongo_store.git' #Rack session store in MongoDB.

# utils

gem 'jammit' #Industrial Strength Asset Packaging for Rails.
gem "whatlanguage", "1.0.0" #A language detection library for Ruby that uses bloom filters for speed
gem "uuidtools", "~> 2.1.1" #- A simple universally unique ID generation library
gem "magent", "0.6.2" # simple job queue system based on mongodb. 
gem "bug_hunter", :git => "git://github.com/ricodigo/bug_hunter.git" #mountable app to track exceptions built on sinatra.

gem 'goalie', '~> 0.0.4' #Custom error pages for Rails 
gem 'dynamic_form' #Helpers to deal with your model backed forms in Rails3
gem 'rinku', '~> 1.2.2', :require => 'rails_rinku'  #Autolinking. Ruby. Yes, that's pretty much it

gem "rack-recaptcha", "0.2.2", :require => "rack/recaptcha" # Rack Middleware for CAPTCHA verification via Recaptcha API.

gem "twitter-text", "1.1.8" #Twitter text processing library (auto linking and extraction of usernames, lists and hashtags)
gem "twitter_oauth" #Twitter OAuth REST API client library for Ruby
gem 'social_widgets', :git => 'https://git.gitorious.org/social_widgets/social_widgets.git' #display widgets of social networks
gem 'activemerchant', '1.16.0' #Active Merchant is a simple payment abstraction library used in and sponsored by Shopify
gem 'pdfkit', :git => 'git://github.com/jdpace/PDFKit.git' ##--- apt-get install wkhtmltopdf---##HTML+CSS to PDF using wkhtmltopdf

gem 'geoip' # The Ruby gem for querying Maxmind.com's GeoIP database, which returns the geographic location of a server given its IP address

# authentication
gem 'omniauth', '~> 0.3.0' #OmniAuth is a flexible authentication system utilizing Rack middleware
gem 'oa-openid', '~> 0.3.0', :require => 'omniauth/openid' #OpenID strategies for OmniAuth.
gem "oa-oauth", '~> 0.3.0', :require => "omniauth/oauth" #OAuth strategies for OmniAuth..

gem 'multiauth', :git => "http://github.com/dcu/multiauth.git" #multiauth - authentication for rails 3 based on omniauth

gem 'orm_adapter' #orm_adapter - Provides a single point of entry for using basic features of ruby ORMs.
gem 'devise', "~> 1.4.0" # Flexible authentication solution for Rails with Warden

gem 'whenever', :require => false #Cron jobs in Ruby
gem 'rack-ssl', :require => false # Rack middleware to force SSL

gem 'state_machine', "0.10.4" #Adds support for creating state machines for attributes on any Ruby class.

#gem "xapian-ruby", '1.2.7.1'
gem  "xapian-full" #Ruby Xapian bindings, including xapian-core.
gem "xapit", :git => "git://github.com/dcu/xapit.git" # High level Ruby library for interacting with Xapian, a full text search engine

group :deploy do
  gem 'capistrano', :require => false #Remote multi-server automation tool
  gem 'ricodigo-capistrano-recipes', "~> 0.1.3", :require => false
  gem 'unicorn', '4.1.1', :require => false #Rack HTTP server for fast clients and Unix
end 

group :scripts do
  gem 'eventmachine', '~> 0.12.10' #EventMachine: fast, simple event-processing library for Ruby programs.
  gem 'em-websocket', '~> 0.3.0' #EventMachine based WebSocket server
  gem 'twitter', '1.7.2' #- A Ruby wrapper for the Twitter REST and Search APIs
end

group :test do
  #gem 'capybara'
  #gem "capybara-webkit"
  #gem 'launchy'
  #gem 'machinist_mongo', :require => 'machinist/mongoid'
  #gem 'ffaker'
  #gem 'simplecov'
  #gem "autotest"
  #gem 'ruby-debug19', '0.11.6', :require => 'ruby-debug'
end

group :development do
  gem "pry" # an IRB alternative and runtime developer console
  gem "database_cleaner" #Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing.
  gem "rspec", ">= 2.0.1"  #Behaviour Driven Development framework for Ruby.
  gem "rspec-rails", ">= 2.0.1" 
  gem "remarkable_mongoid", ">= 0.5.0" #Remarkable Matchers for Mongoid.
  #gem 'hpricot' #- A swift, liberal HTML parser with a fantastic library.
  gem 'why-hpricot' 
  gem 'ruby_parser' #ruby_parser (RP) is a ruby parser written in pure ruby (utilizing racc--which does by default use a C extension)
  gem 'mongrel', '1.2.0.pre2' #Simple Fast Mostly Ruby Web Server
  gem 'niftier-generators', '0.1.2' # Modified version of Ryan Bates nifty-generators
  gem 'ruby-prof' #ruby-prof is a fast code profiler for Ruby.
  gem 'tunnlr_connector', :git => "git://github.com/dcu/tunnlr_connector.git", :branch => "patch-1", :require => "tunnlr"  #A plugin for interacting with tunnlr on both unix and windows. Uses the net::ssh gem.
  gem 'rails-dev-boost', :git => 'git://github.com/thedarkone/rails-dev-boost.git', :require => 'rails_development_boost'# Speed up slow Rails development mode
end
