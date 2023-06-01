# Crystal.tmbundle

TextMate 2 Bundle for [Crystal](crystal-lang.org).

## Install

```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/crystal-lang-tools/Crystal.tmbundle.git
```


## Features

- Build - Compile current file - `CMD + b`
- Run - Run `crystal run $current_file` - `CMD + r`
- Format Code - Auto check and format current file - `CMD + s`
- Test - Run `crystal spec $current_file` - `CMD + SHIFT + r`

## Special `crystal` path.

By default, this bundle will try to call the `crystal` command. You can specify a path via `TM_CRYSTAL` env variable.

```
TM_CRYSTAL=/path/to/your/crystal
```

## Contributors

- [@chris-huxtable](https://github.com/chris-huxtable) Chris Huxtable - creator
- [@hovsater](https://github.com/hovsater) Kevin Hovsäter - maintainer

[See all contributors](https://github.com/crystal-lang-tools/Crystal.tmbundle/graphs/contributors)
