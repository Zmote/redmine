build: rake db:migrate RAILS_ENV=${RACK_ENV:-development}
defaults: rake redmine:load_default_data RAILS_ENV=${RACK_ENV:-development}
web: bundle exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-development}
