web: bundle exec unicorn -p $PORT -c ./config/unicorn.rb
worker:  env QUEUE=* bundle exec rake resque:work
streamer: bundle exec rake stream:run