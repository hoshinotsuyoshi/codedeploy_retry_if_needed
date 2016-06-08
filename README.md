# CodedeployRetryIfNeeded

Retry AWS codedeploy deployment if needed.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'codedeploy_retry_if_needed'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install codedeploy_retry_if_needed

## Usage

```sh
$ DEPLOYMENT_ID="d-xxxxx" \
GITHUB_LOGIN="xxxxxxxxx" \
GITHUB_ACCESS_TOKEN="xxxxxxxxxxxxxxxxxxxxxxxxx" \
codedeploy_retry_if_needed
```

## Note

Supports only "Deployment Config: `CodeDeployDefault.OneAtATime`"

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

