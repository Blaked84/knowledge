## Install tips

### Fix pry or irb history
If you don't have any history in pry or irb or rails console.

- `brew install readline` if it isn't installed already
- `rbenv uninstall 2.3.0`
- `rbenv install 2.3.0`
- Add `IRB.conf[:SAVE_HISTORY] = 100000` to `~/.irbrc`
