# `watch` addon for [todotxt-cli]

Clear terminal and repeat a todo command whenever the todo.txt file changes.

## Install

1. Install `entr` read https://github.com/eradman/entr/ for more details
```
brew install entr                # MacOs with Homebrew
sudo apt-get install entr        # Debian or Ubuntu
```

2. 
```
git clone https://github.com/munkee/todo.txt-watch.git
ln -s todo.txt-watch/watch $TODOTXT_ACTIONS_DIR/watch
```

## Usage

```
Usage
  $ todo.sh watch [COMMAND]
             
  Examples
    $ todo.sh watch ls +project
    $ todo.sh watch lsp @context
```

## License
GPL3

[todotxt-cli]: https://github.com/todotxt/todotxt-cli
