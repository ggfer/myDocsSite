# Mkdocs

## Command

  - `brew install mkdocs`
  - `mkdocs new my-project`
  - `mkdocs serve` to preview documentation
  - `mkdocs build` to creat a new directory called **./site**
  - `mkdocs gh-deploy` push your document site to github pages
  - `sudo easy_install pip` and `pip install mkdocs-material`
  - `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## 分支作用

1. master分支：

  - 本地调试与查看，`mkdocs serve`
  - 贡献者同步。

2. gh-pages分支：

    - 仅仅是`mkdocs gh-deploy`部署到公网页面上，`mkdocs gh-deploy`

## 其他

For full documentation visit [mkdocs.org](https://mkdocs.org).