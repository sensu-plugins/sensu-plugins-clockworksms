## Sensu-Plugins-clockworksms

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-clockworksms.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-clockworksms)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-clockworksms.svg)](http://badge.fury.io/rb/sensu-plugins-clockworksms)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-clockworksms)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-clockworksms.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-clockworksms)
[ ![Codeship Status for sensu-plugins/sensu-plugins-clockworksms](https://codeship.com/projects/e8fdba80-cde6-0132-f83d-36838894891f/status?branch=master)](https://codeship.com/projects/76359)

## Functionality

## Files
 * bin/handler-clockworksms.rb

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

[Installation and Setup](https://github.com/sensu-plugins/documentation/blob/master/user_docs/installation_instructions.md)

## Notes
