release: rake db:migrate && rake db:seed
web: bundle exec bin/rails server -b 0.0.0.0 -p ${PORT:-3000} -e $RAILS_ENV 