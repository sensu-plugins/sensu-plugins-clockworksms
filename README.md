## Sensu-Plugins-clockworksms

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-clockworksms.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-clockworksms)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-clockworksms.svg)](http://badge.fury.io/rb/sensu-plugins-clockworksms)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-clockworksms.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-clockworksms)

## Functionality

## Files
 * bin/handler-clockworksms

## Usage

```
{
    "clockworksms": {
        "key": "1234abc1esg1234abcdfdfg",
        "from": "SENSU",
        "to": {
            "3864153012": [
                "ok",
                "warning"
            ],
            "61431324189": [
                "ok",
                "critical",
                "warning"
            ]
        }
    }
}
```

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-clockworksms -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-clockworksms`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-clockworksms' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-clockworksms' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
