# Writer

A minimalistic and distraction free blog theme for authors and writers, powered by [Hugo](https://gohugo.io).

## Installation

The theme can be installed either as a clone or as a submodule folder from github.

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