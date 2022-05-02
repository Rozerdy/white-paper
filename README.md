# tea.white-paper

```sh
sh <(curl tea.xyz) https://github.com/teaxyz/white-paper
pandoc …  # see below for command line
```

…is what you *will* do—when `tea` is released.
Until then use Homebrew:

```sh
brew install pandoc basictex rsvg pandoc-crossref
make
```

# Dependencies

| Project           | Version |
|-------------------|---------|
| pandoc.org        | ^2.18   |
| gnome.org/librsvg | ^2.54   |