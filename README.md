# Luke's Dotfiles

[Everything in it's right place](https://www.youtube.com/watch?v=onRk0sjSgFU)

## Setup

- Symlink each file into `~/`
- Add the following to your `.zshrc` file
- Keep sensitive information out of `.exports`, `.aliases`, `.functions`. Put them in `.extras` or in `.zshrc`

```sh
# Load ~/.exports, ~/.aliases, ~/.functions
# ~/.extra can be used for settings you don’t want to commit
for file in exports aliases functions extra; do
  file="$HOME/.$file"
  [ -e "$file" ] && source "$file"
done
```

