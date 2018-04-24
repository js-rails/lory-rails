# Lory::Rails
[![Gem Version](https://badge.fury.io/rb/lory-rails.svg)](https://rubygems.org/gems/lory-rails) 
[![Downloads](https://img.shields.io/gem/dt/lory-rails.svg)](https://rubygems.org/gems/lory-rails)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/tanvir002700/lory-rails/master.svg)](https://github.com/tanvir002700/lory-rails)
[![license](https://img.shields.io/github/license/tanvir002700/lory-rails.svg)](https://github.com/tanvir002700/lory-rails/blob/master/LICENSE)

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/lory/rails`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'lory-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install lory-rails
    
And then edit your app/assets/stylesheets/application.js file to look something like:
``` css
/*
*= require_self
*= require jqeury
*= require jquery-ui
*= require lory
*= require_tree .
*/
```

Integration as a jQuery Plugin add jquery.lory
``` css
/*
*= require_self
*= require jqeury
*= require jquery-ui
*= require jquery.lory
*= require_tree .
*/
```

**lory-rails is dependant on jQuery, so make sure you have it in your Gemfile.**

## Usage

View [lory](http://meandmax.github.io/lory) for complete useage information.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/tanvir002700/lory-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Lory::Rails project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/tanvir002700/lory-rails/blob/master/CODE_OF_CONDUCT.md).
