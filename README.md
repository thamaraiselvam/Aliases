# Aliases

Configure aliases/Shell functions more easily.

## Installation

```
cd
git clone https://github.com/thamaraiselvam/Aliases.git
```

Open `~/.zshrc` add include this file

```
for file in ~/.aliases/.*; do source $file; done
```

and finally do `source ~/.zshrc` for reloading configurations
