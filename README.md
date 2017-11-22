# AmchartMaps

Allows easy to use Amcharts maps with the asset pipeline

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'amchart_maps'
```

And then execute:

    $ bundle
    or
    $ bundle install

Or install it yourself as:

    $ gem install amchart_maps

## Usage

In this version, not all amchart_maps are featured, by the way, you can do this [Example](https://www.amcharts.com/demos/grouped-countries-map/).

  > Add this on your assets/javascripts/application.js before `//= require_tree .` as common.
  `//= require ammap
  //= require maps/js/worldHigh
  //= require themes/light`

  > Then use the script of the javascript example file.
## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/vmvwebworks/amchart_maps.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
