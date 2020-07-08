web: rake db:migrate RAILS_ENV=${RACK_ENV:-development} && bundle exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-development}
