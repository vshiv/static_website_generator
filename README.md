# Static site

This website helps generate and test HTML for a static website


## Deploy for the very first time

* Open terminal
* Download and install Ruby
```
https://www.ruby-lang.org/en/documentation/installation/
```
* In the website generator code run
```
sudo gem install bundler
sudo bundle install
```
* To add a new post, add a new .md file in the _posts directory. Check the existing post for info.
* To test code changes run the following command
```
sudo bundle exec jekyll serve --config _config_dev.yml
```
* Open ```http://localhost:4000/``` in a browser to test