# Devise::Basecamper

Devise-Basecamper was built to allow users of Devise to implement "Basecamp" style subdomain scoped authentication with support for multiple users.  There are a lot of great tutorials out there on doing subdomain authentication with devise, but none of them seemed to fit
my particular use case: A subdomain identifies the account, which can have multiple users.  In addition, Devise-Basecamper makes it possible to use the same username/email address for users under different accounts.

## Installation

Add this line to your application's Gemfile:

`gem 'devise-basecamper'`

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install devise-basecamper

## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request