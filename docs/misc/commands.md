# Commands

## Utilities

### Extract tar.gz files

1. Under the tar.gz file contained directory:

```
tar -xzvf file.tar.gz
```

### Deploy mkdocs to github pages

1. Set repository as public in the settings tab
    - ![Upload_this_image_please](../../images/misc/commands/github_01.jpg)
2. Execute this command in the repository parent directory:
    - ```python -m mkdocs gh-deploy ```
