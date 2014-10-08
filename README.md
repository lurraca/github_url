# GithubUrl

Parse the username, repo and protocol from a github clone url. In Ruby.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'github_url'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install github_url

## Usage

```GithubUrl.parse("https://github.com/lurraca/github_url")
#=> #<GithubUrl::Parsed username="lurraca" repo="github_url" protocol="https">
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/github_url/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
