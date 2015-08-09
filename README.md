# Rails Notebook Sample Application

This is an extension of the sample application for
[*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/). 

The aim of this extension is to allow the launch of an ruby notebook for a rails application. 

Some useful resources

http://ipython.org/notebook.html
https://github.com/SciRuby/iruby

This will be done by extending iRuby and using a rake task 

Setup :

    cd /tmp
    git clone https://github.com/railstutorial/sample_app_rails_4.git
    cd sample_app_rails_4
    cp config/database.yml.example config/database.yml
    bundle install --without production
    bundle exec rake db:migrate
    bundle exec rake db:test:prepare
    bundle exec rspec spec/

