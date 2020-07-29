# Ask Sphinx

Use the quickstart template and enter in Project Name, Authors, and Versions.

```
sphinx-quickstart
```

Add the following to **config.py**

```
import sphinx_rtd_theme
import recommonmark
```

```
extensions = [
    "sphinx_rtd_theme",
    "recommonmark"
]
```

```
html_theme = 'sphinx_rtd_theme'
```
