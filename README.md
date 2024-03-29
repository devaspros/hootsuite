# Hootsuite

Ruby wrapper for the Hootsuite API.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'hootsuite'
```

And then execute:

```
$ bundle install
```

Or install it yourself as:

```
$ gem install hootsuite
```

## Usage

Copy `.env.example` to `.env.local` and setup env vars:

```shell
HOOTSUITE_ACCESS_TOKEN="YOUR_CONSUMER_KEY"
CLIENT_ID="HOOTSUITE_CLIENT_ID"
SECRET_ID="HOOTSUITE_SECRET_ID"
REDIRECT_URI="https://redirecturl.com"
```

Run local server to test OAuth integration:

```
$ ruby local_server.rb
```

and go to `localhost:4567`.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/devaspros/hootsuite.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
