# Writer

A minimalistic and distraction free blog theme for authors and writers, powered by [Hugo](https://gohugo.io).

## Installation

The theme can be installed either as a clone or as a submodule folder from github.

### Install as clone

In your Hugo site `themes` directory, run:

```
$ git clone https://github.com/shazic/writer
```

### Install as submodule

From the root of your Hugo site, type the following:

```
$ git submodule add https://github.com/shazic/writer.git themes/writer
$ git submodule init
$ git submodule update
```

You can get updates to the theme Writer in the future by updating the submodule:

```
$ git submodule update --remote themes/writer
```

## Configuration

After installation, take a look at the `exampleSite` folder inside `themes/writer`.

To get started, copy the `config.toml` file inside `exampleSite` to the root of your Hugo site:

```
$ cp themes/writer/exampleSite/config.toml .
```

Now edit this file and add your own information. 

In order to use the theme's archetypes, delete your site's `archetypes/default.md`.

For more information read the official [theme installation guide](https://gohugo.io/themes/installing-and-using-themes/) of Hugo.

## Contributing

Have you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//github.com/shazic/writer/issues) to let me know. Or make directly a [pull request](//github.com/shazic/writer/pulls).

## License

This theme is released under the [MIT license](//github.com/shazic/writer/blob/master/LICENSE.md).