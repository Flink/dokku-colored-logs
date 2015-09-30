# (DEPRECATED) dokku-colored-logs

THIS PLUGIN IS NOW DEPRECATED SINCE IT HAS BEEN INCLUDED DIRECTLY IN DOKKU

dokku-colored-logs is a plugin for [dokku][dokku] that outputs colored logs with named containers (like on Heroku).

## Installation

This plugin is compatible with dokku 0.3.26 and 0.4+

```sh
# for dokku 0.3.26
$ sudo git clone https://github.com/Flink/dokku-colored-logs.git /var/lib/dokku/plugins/colored-logs

# for dokku 0.4+
$ sudo dokku plugin:install https://github.com/Flink/dokku-colored-logs.git
```

## Usage

```shell
$ dokku help
   logs:color <name> [-t]     Show the last logs for an application (-t follows)
```

## License

This plugin is released under the MIT license. See the file [LICENSE](LICENSE).

[dokku]: https://github.com/progrium/dokku

