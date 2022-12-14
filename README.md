Rspec:
bundle add rspec-rails
rails generate rspec:install

React:
bundle add webpacker
bundle add react-rails
rails webpacker:install
rails webpacker:install:react
yarn add @babel/preset-react
yarn add @rails/activestorage
yarn add @rails/ujs
rails generate react:install
rails generate react:component App

Devise:
bundle add devise
rails generate devise:install
rails generate devise User
rails db:migrate

Bootstrap: 
bundle add bootstrap
mv app/assets/stylesheets/application.css app/assets/stylesheets/application.scss
yarn add reactstrap

Data:
