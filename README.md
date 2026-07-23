# cantscroll

focus when you're coding.

cantscroll watches for ai coding agents (claude code, cursor, codex,
antigravity) running on your mac. the moment one starts working, your
paired iphone locks its distracting apps — instagram, tiktok, x, whatever
you pick — until the session ends. no timers, no willpower.

this repo hosts the mac agent's release artifacts (the homebrew formula
points here). the source is closed.

## install

```bash
brew tap cantscroll/cantscroll
brew install cantscroll
brew services start cantscroll/cantscroll/cantscroll
```

then pair your iphone: `cantscroll pair` shows a qr code the cantscroll
app scans to connect.

the mac agent is free and detects your coding agents. the iphone app
(app store link coming soon) is a subscription: $59.99/year with a
3-day free trial, or $7.99/month.

## links

- [cantscroll.com](https://cantscroll.com)
- [privacy policy](https://cantscroll.com/privacy)
- [terms of use](https://cantscroll.com/terms)

## support

found a bug? [open an issue](https://github.com/cantscroll/cantscroll/issues).
anything else: hello@cantscroll.com

## license

binaries in this repo are distributed under a proprietary license — see
[cantscroll.com/terms](https://cantscroll.com/terms). all rights reserved.
