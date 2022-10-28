# my personal nitpick styles for python development

## usage (using pipenv)
* install [nitpick](https://nitpick.readthedocs.io/en/latest/index.html)
```bash
pipenv install nitpick --dev
```

* initialize
```bash
pipenv run nitpick init github://ryo-murai/python-nitpick-styles/nitpick-python-styles.toml

# or use aws-sam style. 
pipenv run nitpick init github://ryo-murai/python-nitpick-styles/nitpick-aws-sam-styles.toml
# aws-sam style include above basic style
```

* create / update configs
```bash
# check
pipenv run nitpick check
# or apply(create or update) files
pipenv run nitpick fix
```

* in case using non-UTF console
```bash
PYTHONUTF8=1 pipenv run nitpick check
```