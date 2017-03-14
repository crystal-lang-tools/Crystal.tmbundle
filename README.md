Crystal.tmbundle
================

TextMate 2 Bundle for [Crystal](crystal-lang.org).

Install
-------

```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles
cd ~/Library/Application\ Support/Avian/Bundles
git clone https://github.com/huacnlee/Crystal.tmbundle.git
```


### Features

- Build - Compile current file - `CMD + b`
- Run - Run `crystal spec` - `CMD + r`
- Format Code - Auto check and format current file - `CMD + s`

### Special `crystal` path.

By default, this bundle will try call `crystal` command, and you can special a path via `TM_CRYSTAL` env.

```
TM_CRYSTAL=/path/to/your/crystal
```
