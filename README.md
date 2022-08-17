## Getting started

### ecom-app-with-solidus-frontend

rails new store --skip-javascript
cd store

bundle add solidus_core solidus_backend solidus_api solidus_sample

bin/rails generate solidus:install --auto-accept

LOCATION="https://raw.githubusercontent.com/solidusio/solidus_starter_frontend/master/template.rb" \
 bin/rails app:template
