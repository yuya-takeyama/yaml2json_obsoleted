# Yaml2json

Command to convert from YAML to JSON

## Installation

Add this line to your application's Gemfile:

    gem 'yaml2json'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install yaml2json

## Usage

### Read from files

```
$ yaml2json file1.yml file2.yml
```

### Read from STDIN

```
$ tail -F file.yml | yaml2json
```

## Contributing

1. Fork it ( https://github.com/yuya-takeyama/yaml2json/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
