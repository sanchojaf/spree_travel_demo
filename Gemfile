CONFIG = :snc
###########################################################################
case CONFIG
when :pqr
  GEMS_PATH = 'http://localhost/rubygems/'
  SPREE_PATH = 'file:///home/pqr/work/jaf/spree'
  SPREE_TRAVEL_PATH = 'file:///home/pqr/work/jaf/openjaf'
when :snc
  GEMS_PATH = 'file:///home/test/.rvm/gems/ruby-1.9.3-p392/bundler/gems/'
  SPREE_PATH = 'file:///media/Data/jaf/spree'
  SPREE_TRAVEL_PATH = 'file:///media/Data/jaf/spree_travel'
when :raul
  GEMS_PATH = 'http://localhost/rubygems/'
  SPREE_PATH = 'file:///home/raul/RubymineProjects/spree'
  SPREE_TRAVEL_PATH = 'file:///home/raul/RubymineProjects/openjaf'
else
  GEMS_PATH = 'http://rubygems.org'
  SPREE_PATH = 'https://github.com/spree'
  SPREE_TRAVEL_PATH = 'https://github.com/openjaf'
end
###########################################################################

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
gem 'spree',                      :git => "#{SPREE_PATH}/spree", :branch => '2-0-stable'
gem 'spree_auth_devise',          :git => "#{SPREE_PATH}/spree_auth_devise", :branch => '2-0-stable'
gem 'spree_related_products', 	  :git => "#{SPREE_PATH}/spree_related_products"

#gem 'spree_static_content',       :git => "#{SPREE_PATH}/spree_static_content", :branch => '2-0-stable'
#gem 'spree_paypal_express',       :git => "#{SPREE_PATH}/spree_paypal_express", :branch => '2-0-stable'
#gem 'spree_product_groups',       :git => "#{SPREE_PATH}/spree_product_groups", :branch => '2-0-stable'
#gem 'spree_wishlist',             :git => "#{SPREE_PATH}/spree_wishlist", :branch => '2-0-stable'
#gem 'spree_email_to_friend',      :git => "#{SPREE_PATH}/spree_email_to_friend", :branch => '2-0-stable'
#gem 'spree_reviews',              :git => "#{SPREE_PATH}/spree_reviews", :branch => '2-0-stable'
#gem 'spree_recently_viewed',      :git => "#{SPREE_PATH}/spree_recently_viewed"
#gem 'spree_social',               :git => "#{SPREE_PATH}/spree_social"
#gem 'spree_editor',               :git => "#{SPREE_PATH}/spree_editor'

#gem 'spree_fancy',                :git => "#{SPREE_PATH}/spree_fancy", :branch => '2-0-stable'

#SPREE_TRAVEL_GEMS
gem 'spree_property_type', 		  :git => "#{SPREE_TRAVEL_PATH}/spree_property_type"
gem 'spree_travel', 			  :git => "#{SPREE_TRAVEL_PATH}/spree_travel"
gem 'spree_location',             :git => "#{SPREE_TRAVEL_PATH}/spree_location"
gem 'spree_travel_rentacar',      :git => "#{SPREE_TRAVEL_PATH}/spree_travel_rentacar"
gem 'spree_travel_sample',        :git => "#{SPREE_TRAVEL_PATH}/spree_travel_sample"
#gem 'spree_travel_ota',           :git => "#{SPREE_TRAVEL_PATH}/spree_travel_ota"

#gem 'spree_travel_accommodation',:git => "#{SPREE_TRAVEL_PATH}/spree_travel_accommodation"
#gem 'spree_travel_destination',  :git => "#{SPREE_TRAVEL_PATH}/spree_travel_destination"
#gem 'spree_travel_flight',       :git => "#{SPREE_TRAVEL_PATH}/spree_travel_flight"
#gem 'spree_travel_point',        :git => "#{SPREE_TRAVEL_PATH}/spree_travel_point"
#gem 'spree_travel_program',      :git => "#{SPREE_TRAVEL_PATH}/spree_travel_program"
#gem 'spree_travel_route',        :git => "#{SPREE_TRAVEL_PATH}/spree_travel_route"
#gem 'spree_travel_tour',         :git => "#{SPREE_TRAVEL_PATH}/spree_travel_tour"
#gem 'spree_travel_transfer',     :git => "#{SPREE_TRAVEL_PATH}/spree_travel_transfer"
