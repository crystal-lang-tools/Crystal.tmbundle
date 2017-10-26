Crystal.tmbundle
================

TextMate 2 Bundle for [Crystal](crystal-lang.org).

Install
-------

```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/crystal-lang-tools/Crystal.tmbundle.git
```


### Features

- Build - Compile current file - `CMD + b`
- Run - Run `crystal run $current_file` - `CMD + r`
- Format Code - Auto check and format current file - `CMD + s`
- Test - Run `crystal spec $current_file` - `CMD + SHIFT + r`

### Special `crystal` path.

By default, this bundle will try call `crystal` command, and you can special a path via `TM_CRYSTAL` env.

```
TM_CRYSTAL=/path/to/your/crystal
```
