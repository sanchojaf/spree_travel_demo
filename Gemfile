# Configuracion de PQR
GEMS_PATH = 'http://localhost/rubygems/'
SPREE_PATH = 'file:///home/pqr/work/jaf/spree'
########################################################################

source GEMS_PATH

gem 'rails', '3.2.13'
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

gem 'spree', '2.0.3'
#gem 'spree', :git => "#{SPREE_PATH}/spree/", :branch => '2-0-stable'
gem 'spree_auth_devise', :git => "#{SPREE_PATH}/spree_auth_devise/", :branch => '2-0-stable'
gem 'spree_related_products', :git => "#{SPREE_PATH}/spree_related_products/", :branch => 'master'
gem 'spree_property_type', :path => '../spree_property_type'
gem 'spree_travel', :path => '../spree_travel'
gem 'spree_location', :path => '../spree_location'
gem 'spree_travel_rentacar',      :path => '../spree_travel_rentacar'
#gem 'spree_travel_accommodation', :path => '../spree_travel.git/spree_travel_accommodation'
#gem 'spree_travel_destination',   :path => '../spree_travel.git/spree_travel_destination'
#gem 'spree_travel_flight',        :path => '../spree_travel.git/spree_travel_flight'
#gem 'spree_travel_point',         :path => '../spree_travel.git/spree_travel_point'
#gem 'spree_travel_program',       :path => '../spree_travel.git/spree_travel_program'
#gem 'spree_travel_route',         :path => '../spree_travel.git/spree_travel_route'
#gem 'spree_travel_tour',          :path => '../spree_travel.git/spree_travel_tour'
#gem 'spree_travel_transfer',      :path => '../spree_travel.git/spree_travel_transfer'
