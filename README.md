# my personal nitpick styles

## usage (using pipenv)
* install [nitpick](https://nitpick.readthedocs.io/en/latest/index.html)
```bash
pipenv install nitpick --dev
```

* initialize
```bash
pipenv shell
nitpick init github://ryo-murai/python-nitpick-styles/nitpick-style.toml

# or use aws-sam style. 
nitpick init github://ryo-murai/python-nitpick-styles/nitpick-aws-sam-style.toml
# aws-sam style include above basic style
```

* create / update configs
```bash
# check
nitpick check
# or apply(create or update) files
nitpick fix
```

* use pipenv run in CI
```bash
pipenv run nitpick-check
```