# README

Setup

Run `bundle install`
Run `rails db:migrate`
Create env variable `PEXELS_API_KEY` and set the value to your key
Install imagemagick `sudo apt install imagemagick`
Run `rails db:seed`

You are now ready to run the server with `rails s`!

If you encounter ruby version errors, if you are using rbenv you can resolve with these commands:
`rbenv install 3.2.0`
`rbenv local 3.2.0`
