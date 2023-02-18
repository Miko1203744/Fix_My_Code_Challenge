README Blog application:

How to install it: Follow the instructions here or here to install rvm and ruby 2.3. $ gem install bundler:1.14.1 $ apt-get install ruby-dev make gcc g++ sqlite3 libsqlite3-dev zlib1g zlib1g-dev tzdata $ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash - $ sudo apt-get install -y nodejs $ bundle install --path=vendor/bundle $ cp -r vendor/bundle/ruby/2.3.0/* /usr/share/rvm/gems/ruby-2.3.1@fmcc_01/ $ rvm gemset use fmcc_01 $ rails db:migrate RAILS_ENV=development How to run the server $ rails s -b 0.0.0.0 -p 5000
