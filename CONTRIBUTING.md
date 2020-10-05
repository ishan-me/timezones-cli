## How to contribute to Good First Issues

Thank you for considering contributing to `timezones-cli`!

### Submitting Updates

Include the following in your patch:

- Use [Black](https://github.com/psf/black) to format your code. This and other tools will run automatically if you install [pre-commit](https://github.com/pre-commit/pre-commit-hooks) using the instructions below.

- Update README.md about new changes if it affects the sub-commands.

- Use [mypy](https://github.com/python/mypy) to check static typing on the codebase.

### First time setup

- Clone the repo locally.

```bash
    $ git clone https://github.com/yankeexe/timezones-cli
```

- Create a virtualenv

```bash
    $ make venv

    # activate virtualenv
    $ source venv/bin/activate
```

### Install timezone-cli in editable mode with development dependencies.

```bash
    $ make setup
```

### Install the pre-commit hooks.

```bash
    $ pre-commit install
```

Start coding 🚀
