# Isis plugin: Weather Report

This plugin adds a weather command to the [Isis chatbot](https://github.com/silentgrowl/isis)

## Installation

Copy config/weather.csv.example from the gem repo and save as ```config/weather.csv``` in your Isis installation.

Edit the config/weather.csv file to be a comma-separated list of ZIP codes to include in the weather report.

Add this line to your Isis installation's Gemfile:

``ruby
gem 'isis-plugin-weather'
``

And then execute:

    $ bundle

## Usage

Post the latest weather forecast into a room by typing ```!weather``` in chat.

## Links

* [isis-plugin-weather on RubyGems](https://rubygems.org/gems/isis-plugin-weather)
