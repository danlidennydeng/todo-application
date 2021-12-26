https://stevepolito.design/blog/rails-react-tutorial/

Ruby 2.7.1, yarn 1.22.5, Rails 6.0.4.4, node v16.13.1

rails new todo-application -d=postgresql --webpacker=react
cd todo-application
rails db:create
rails s

Webpacker::Manifest::MissingEntryError

yarn add @rails/webpacker

yarn list webpack

#webpack@4.46.0 got installed
--------------------------------------------------------------

{
error: "You need to sign in or sign up before continuing."
}

This error message shows before unauthorized.json.jbuilder was even created. It comes from config/locales/devise.en.yml

