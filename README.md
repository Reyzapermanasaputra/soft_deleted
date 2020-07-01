# SafeDeleted
This is only simple gem for updating data from active to inactive and get data based on active or inactive.

## Usage
Make sure your model have field is_active with type boolean.

## Installation
Add this line to your application's Gemfile:

```ruby
gem 'safe_deleted'
```

And then execute:
```bash
$ bundle
```

Or install it yourself as:
```bash
$ gem install safe_deleted
```

add your model or in application_record.rb :
```bash
$ include SafeDeleted::ActsAsSafeDeleted
```

## License
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).