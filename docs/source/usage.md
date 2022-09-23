# Usage

## Installation

To use Lumache, first install it with `pip`:

```console
(.venv) $ pip install lumache
```

## Creating recipes

To retrieve a list of ingredients,
use the {py:func}`lumache.get_random_ingredients` function.

The `kind` parameter should be a {py:class}`str`,
otherwise the function will raise the exception {py:exc}`lumache.InvalidKindError`.

```{eval-rst}
.. autosummary::
   :toctree: _autosummary
   :template: custom-module-template.rst
   :recursive:

   lumache
```
