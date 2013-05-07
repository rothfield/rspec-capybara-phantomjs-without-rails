rspec capybara selenium without rails
=====================================

Using RSpec and Capybara Without Rails - with PhantomJS driver (Poltergeist)

This is a simple project that uses Rspec without Rails. In this example, the single test tests youtube.com

Based on: Implementation of Jeff Nyman's article [Using RSpec and Capybara Without Rails](http://testerstories.com/?p=30)

In this sample app I use PhantomJS as the Capybara driver.

Installation
-----------

git clone git@github.com:rothfield/rspec_capybara_selenium_without_rails.git
bundle install --binstubs

# You may have to edit the file spike_capybara_spec.rb to set the firefox path.
# Then to run the tests:
spec
