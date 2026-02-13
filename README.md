# MkDocs Theme

This is the default theme for MkDocs version 2, currently in development.

Installable by including the URL in the `mkdocs.toml` config...

```toml
[mkdocs]
nav = [
    {path="README.md", title="Readme"}
]

[loaders]
theme = "https://github.com/lovelydinosaur/mkdocs-theme/archive/refs/heads/main.zip"
docs = "dir://docs"
```

The default theme is also included in the installable package, and can be loaded directly...

```toml
[loaders]
theme = "pkg://mkdocs/default"
docs = "dir://docs"
```
