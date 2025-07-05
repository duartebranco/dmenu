# duartebranco's dmenu

This is my personal build of dmenu with several patches and customizations applied.

You probably should make your own builds, since it's in the "suckless" mindset to know your programs and have only exactly what you want in them.

## Patches/Changes Included

- Centered menu (`dmenu-center`)
- Grid layout support (`dmenu-grid`)
- Fuzzy matching (`dmenu-fuzzymatch`)
- Case-insensitive matching by default (`dmenu-caseinsensitive`)
- Highlight matched text (`dmenu-highlight`)
- Mouse support (`dmenu-mousesupport`)
- Show number of matches (`dmenu-numbers`)

*(See the `patches/` directory for details on each patch.)*

## Compilation

To build and install dmenu, run:

```sh
make clean install
```

You might need to use `sudo` for installation.
