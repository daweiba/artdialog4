# Artdialog4

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/artdialog4`. To experiment with that code, run `bin/console` for an interactive prompt.

Artdialog是一个国人开发的dialog组件，升级后需要sea.js 或 require.js
而4.0版本用起来还挺顺手，于是封装成gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'artdialog4'
```
或
```ruby
gem 'artdialog4' , github: 'daweiba/artdialog4'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install artdialog4

## Usage
js部分as :

    //= require jquery.artDialog

css 部分 :

    *= require simple

其中simple是样式

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/daweiba/artdialog4/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
