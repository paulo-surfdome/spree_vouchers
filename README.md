SpreeVouchers
=============

This is an incomplete implemenation and is under heavy development

The extension allows the purchase and (full or partial) redemption of vouchers.

Vouchers are treated as payment methods.

Authorize, Capture, Void, and Credit are supported.

Installation
------------

Add spree_vouchers to your Gemfile:

```ruby
gem 'spree_vouchers'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_vouchers:install
```

Testing
-------

Be sure to bundle your dependencies and then create a dummy test app for the specs to run against.

```shell
bundle
bundle exec rake test_app
bundle exec rspec spec
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_vouchers/factories'
```

Copyright (c) 2014 Jeff Squires, released under the New BSD License
