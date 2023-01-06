# 'Latvian - International' key layout for Mac

Default 'Latvian' key layout on MacOS 13
introduces symbols that do not match the ones on the physical keyboard.

This custom key layout has 3 changes to fix the situation.

- <code>Shift</code> + <code>3</code> = <code>#</code> (instead of <code>£</code>)
- <code>Shift</code> + <code>§</code> = <code>±</code> (instead of <code>#</code>)
- Lower left <code>'</code> replaced with <code>`</code>

## Installation

1. Download files from this repository
2. Copy Latvian-International.bundle to `~/Library/Keyboard Layouts/`
manually or via Terminal:

```zsh
cp -R Latvian-International.bundle `~/Library/Keyboard Layouts/`
```

3. Restart

## Set keyboard layout

1. Go to Keyboard layout menu
2. Search for "Latvian - International"

## Known issues

- On MacOS 13 it is impossible to have to a custom keyloayout as the only
  system layout.
  At least one default Latin keylayout must be also be enabled (e.g. US).
  If you find a way to bypass this, be welcome to ping me
  or make a pull-request 😉.

## Credits

Inspiration and Latvian flag icon taken from <https://github.com/duksis/Latvian-pounded.keylayout>.
