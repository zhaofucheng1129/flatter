# flatter

Faced with similar problem?

> 🚨 `error: unable to spawn process (Argument list too long)`

Until [Apple fixes problem](http://www.openradar.me/35879960) you can use `flatter` as workaround solution.

Flatter is a gem which simply move all swift files in Xcode project to root group. That's all :)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'xcflatter'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install xcflatter

## Usage

Simple

    $ flatter "/path/to/your/project.xcodeproj"

Specific group

    $ flatter "/path/to/your/project.xcodeproj" -g "SpecificGroup"

Advanced

    $ flatter "/path/to/your/project.xcodeproj" -g "SpecificGroup" -e ".xib"

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/gregoryvit/flatter.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).