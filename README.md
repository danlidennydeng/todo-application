Ruby 2.7.1, yarn 1.22.5, Rails 6.0.4.4, node v16.13.1

Webpacker::Manifest::MissingEntryError

yarn add @rails/webpacker

#webpack@4.46.0 got installed

rails server

---------------------------------------------------------------

rails generate devise:install

error: "Could not find generator devise:install."

leigh@leigh-VirtualBox:~/Projects/dev01$ gem uninstall devise
Successfully uninstalled devise-3.2.4
leigh@leigh-VirtualBox:~/Projects/dev01$ gem uninstall warden
Successfully uninstalled warden-1.2.3
leigh@leigh-VirtualBox:~/Projects/dev01$ bundle install


closed old terminal and open a new one, then

"rails generate devise:install" again
-------------------------------------------------------------------

Uncaught Error: Cannot find module '@popperjs/core'
# this error appears on F12 console. Bootstrap 5 requires "Popper.js Core", not Popper.js

yarn add @popperjs/core

--------------------------------------------------------------------
--------------------------------------------------------------

{
error: "You need to sign in or sign up before continuing."
}

This error message shows before unauthorized.json.jbuilder was even created. It comes from config/locales/devise.en.yml

