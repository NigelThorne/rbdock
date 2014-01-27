# rbdock

Generate Dockerfile which is installs ruby.

## Installation

Add this line to your application's Gemfile:

    gem 'rbdock'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rbdock

## Usage

```
$ rbdock create 2.0.0-p353
$ rbdock create 2.0.0-p353 -i centos
$ rbdock create 2.0.0-p353 1.9.3-p484 -i ubuntu
```


## Contributing

1. Fork it ( http://github.com/<my-github-username>/rbdock/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
