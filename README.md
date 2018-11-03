# CORAL

CORAL is an in-development scripting language for Discord. The idea is that it will provide functionality to bots such that users and developers may store scripts to be called by events, impliment flags that can extrapolate finer details in events, as well as interpret scripts on-the-fly, for memes and shitposts. The standard library will have everything you need to get started -- ideally, you could build a repetoir of scripts that may call one another in order to build a more functional library for yourself.

Why? To reduce hard-coded functionality and control bot functionality without re-deployment and re-compilation for changes.

A deep permissions system will allow for strict control over what users do and do not have access to within this library.

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  CORAL:
    github: vardy/CORAL
```

## Usage

```crystal
require "CORAL"
```

TODO: Write usage instructions here

## Contributing

1. Fork it (<https://github.com/vardy/CORAL/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [vardy](https://github.com/vardy) Jarred Vardy - creator, maintainer
