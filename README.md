# Color Builder
Easily build color variations of Solarized with YAML scheme definitions and ERB templates.

I'm currently using this to generate
[parsec](https://github.com/Keithbsmiley/parsec)

## Usage
    > ./build
Build all schemes

    > ./build default.yml
Build only the "default" theme

    > ./build https://awesome-schemes.com/my-scheme.yml
Build a scheme stored on some webspace.

## Templates
- iTerm 2
- Vim
- Xcode


### Adding templates

- Grab the corresponding
  [solarzied](https://github.com/altercation/solarized) colorscheme and
  extract the colors out as variables. You can see some examples
  [here](https://github.com/Keithbsmiley/color-builder/tree/master/templates)
  or look at the
  [base16-builder](https://github.com/chriskempson/base16-builder/tree/master/templates)
  templates. If there isn't any difference between the solarized and
  base16 templates besides the colors than you can just grab the
  base16 version and add that.
- Otherwise create [an
  issue](https://github.com/Keithbsmiley/color-builder/issues) and I
  will get to it as soon as I have a chance.

---

This is entirely copied from
[base16-builder](https://github.com/chriskempson/base16-builder) and
[solarized](https://github.com/altercation/solarized)
