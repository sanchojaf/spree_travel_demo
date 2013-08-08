MODE = 'git'  #REMOTE MODE
#MODE = 'path' #LOCAL MODE

# REMOTE CONFIGURATION (DEFAULT)
GEMS_PATH = 'http://rubygems.org'
SPREE_PATH = 'https://github.com/spree'
SPREE_TRAVEL_PATH = 'https://github.com/openjaf'

## lOCAL PQR CONFIGURATION
#GEMS_PATH = 'http://localhost/rubygems/'
#SPREE_PATH = 'file:///home/pqr/work/jaf/spree'
#SPREE_TRAVEL_PATH = '..'

##################################################

source GEMS_PATH

gem 'rails', '3.2.14'
gem 'sqlite3'
gem 'json'
gem 'jquery-rails'
gem 'google_static_maps_helper'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
end

#SPREE_GEMS
gem 'spree',                      :git => "#{SPREE_PATH}/spree", 					:branch => '2-0-stable'
gem 'spree_auth_devise', 		  :git => "#{SPREE_PATH}/spree_auth_devise", 		:branch => '2-0-stable'
gem 'spree_related_products', 	  :git => "#{SPREE_PATH}/spree_related_products"

#SPREE_TRAVEL_GEMS
gem 'spree_property_type', 		   :"#{MODE}" => "#{SPREE_TRAVEL_PATH}/spree_property_type"
gem 'spree_travel', 			   :"#{MODE}" => "#{SPREE_TRAVEL_PATH}/spree_travel"
gem 'spree_location',              :"#{MODE}" => "#{SPREE_TRAVEL_PATH}/spree_location"
gem 'spree_travel_rentacar',       :"#{MODE}" => "#{SPREE_TRAVEL_PATH}/spree_travel_rentacar"

#gem 'spree_travel_accommodation',:#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_accommodation"
#gem 'spree_travel_destination',  :#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
#gem 'spree_travel_flight',       :#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
#gem 'spree_travel_point',        :#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
#gem 'spree_travel_program',      :#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
#gem 'spree_travel_route',        :#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
#gem 'spree_travel_tour',         :#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
#gem 'spree_travel_transfer',     :#{MODE} => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
