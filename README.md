# Hyde-d

__`hyde-d`__ is a fork of [Hyde-hyde](https://github.com/htr3n/hyde-hyde) with small adjustments.

## Usage


### Installation

__`Hyde-d`__ can be installed as many other Hugo themes:

```sh
$ cd HUGO_PROJECT

# then either clone
$ git clone https://github.com/jensen-erik/hyde-d.git themes/hyde-d

# or just add as a submodule
$ git submodule add https://github.com/jensen-erik/hyde-d.git themes/hyde-d
```

After that, choose `hyde-d` as the main theme.

* `config.toml` 

```toml
theme = "hyde-d"
```

* `config.yaml`

```yaml
theme : "hyde-d"
```


### Options

__`Hyde-d`__ essentially inherits Hyde-hyde's [options](https://github.com/htr3n/hyde-hyde#options). 


### Additional options

It is possible to set a custom title on the post list page. The custom title is set in the config file (e.g. to Articles)

```toml
postTitle = "Articles"
```
```yaml
postTitle : "Articles"
```


## License

Open sourced under the [MIT license](LICENSE.md)
