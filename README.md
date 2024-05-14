<h1 align="center">Interactive cheatsheets</h1>

![How it works](https://gist.githubusercontent.com/Farid-NL/02111c0cec350050e4b4c44dbc30f96c/raw/ad4893bee05d05fca9c7573c5040a02cb127200e/cheatsheets.gif)

<p align="center">Powered by <a href="https://github.com/denisidoro/navi">navi</a></p>

## Cheatsheets

- Git
- Docker
- Rbenv
- Text

## Dependencies

### [Eza](https://github.com/eza-community/eza)

For listing files in tree form with pretty icons

```shell
eza -TD --color=always --icons=always
```

![](https://gist.githubusercontent.com/Farid-NL/02111c0cec350050e4b4c44dbc30f96c/raw/d342c5c2507ec8259770f0e2af13c8d361f0de18/eza-tree-icons-color.png)

### Git log alias

For listing commits in a understanable way

```ini
# ~/.gitconfig
[alias]
  lg = "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) -%C(auto)%d%C(reset) %C(white)%s%C(reset)'"
```

![](https://gist.githubusercontent.com/Farid-NL/02111c0cec350050e4b4c44dbc30f96c/raw/d342c5c2507ec8259770f0e2af13c8d361f0de18/git-lg.png)
