[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-hipchat.svg?branch=master)][1]
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-hipchat.svg)][2]
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-hipchat/badges/gpa.svg)][3]
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-hipchat/badges/coverage.svg)][4]
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-hipchat.svg)][5]

## Functionality

## Files
 *
 *
 *
 *

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-hipchat -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-hipchat`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-hipchat' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-hipchat' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

## Notes

[1]:[https://travis-ci.org/sensu-plugins/sensu-plugins-hipchat]
[2]:[http://badge.fury.io/rb/sensu-plugins-hipchat]
[3]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-hipchat]
[4]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-hipchat]
[5]:[https://gemnasium.com/sensu-plugins/sensu-plugins-hipchat]
