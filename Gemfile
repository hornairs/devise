source "http://rubygems.org"

gemspec

gem "rails", "~> 4.0.0.beta", github: "rails/rails"
gem "omniauth", "~> 1.0.0"
gem "omniauth-oauth2", "~> 1.0.0"
gem "rdoc"

group :test do
  gem "omniauth-facebook"
  gem "omniauth-openid", "~> 1.0.1"
  gem "mocha", "0.10.0", :require => false
end

platforms :jruby do
  gem "activerecord-jdbc-adapter"
  gem "activerecord-jdbcsqlite3-adapter"
  gem "jruby-openssl"
end

platforms :ruby do
  gem "sqlite3"
end
