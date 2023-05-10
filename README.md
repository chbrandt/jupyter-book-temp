# jupyter-book-start

To push \_build/html to gh-pages, use `ghp-import`:

```bash
# Check book/_build/html are their
#
jupyter-book build book/
```

```bash
# Install ghp-import if not yet
#
pip install ghp-import
```

```bash
# Let ghp-import handle gh-pages branch
#
ghp-import -n -p -f _build/html
```

