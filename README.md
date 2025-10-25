# MacOS US International without dead keys

> [!WARNING]
> This is slightly modified to make swedish characters (å, ä, ö) work as expected.

## Installation

1. To install the keyboard layout open `Terminal` on your mac and execute the command below.

```
curl -sL https://api.github.com/repos/h4ckint0sh/macos-us-intl-no-dead-keys/tarball/main | sudo tar xz --exclude=README.md --exclude=KeyboardLayout.png --strip=1 -C /Library/Keyboard\ Layouts/
```

2. Enter your password. This is required because the keyboard layout is installed for all users on your mac.
3. Open `System Preferences` -> `Keyboard` -> `Input Sources`
4. Click `+` and add `US Intl without dead keys` (category `English`) (Note: If the keyboard is not displayed, you may have to restart your device)
5. Check `☑ Show Input menu in menu bar`.
6. In the menu bar (top right) select `US Intl without dead keys`.

