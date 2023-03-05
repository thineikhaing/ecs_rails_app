#Procfile allows for more startup configuration and the definition of multiple processes
web: bundle exec puma -C config/puma.rb
worker: bundle exec sidekiq -C config/sidekiq.yml
