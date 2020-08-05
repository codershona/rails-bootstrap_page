# README

## Project: Rails Bootstrap Page App
## Styling the Application using Bootstrap 4

## Run rails s


Then visit (http://localhost:3000/#) in the browser to see the bootstrap page.

## Instructions :


# Add `bootstrap` to your Gemfile:

```ruby
STEP 1: gem 'bootstrap', '~> 4.4.1'   


Make sure the file has `.scss` extension (or `.sass` for Sass syntax). If you have just generated a new Rails app,
it may come with a `.css` file instead. If this file exists, it will be served instead of Sass, so rename it:


STEP 2:
```console
 $ mv app/assets/stylesheets/application.css app/assets/stylesheets/application.scss

Import Bootstrap styles in `app/assets/stylesheets/application.scss`:


STEP 3: 
```scss
// Custom bootstrap variables must be set or imported *before* bootstrap.
@import "bootstrap";


STEP 4:
Bootstrap JavaScript depends on jQuery.
If you're using Rails 5.1+, add the `jquery-rails` gem to your Gemfile:

```ruby
gem 'jquery-rails'

STEP 5:

Add Bootstrap dependencies and Bootstrap to your `application.js`:
//= require popper
//= require bootstrap-sprockets

STEP 6: 

   Run bin/bundle /or, bundle install .or, bundle install --without production

