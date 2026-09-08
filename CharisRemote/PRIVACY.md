# CharisRemote Privacy Statement

Effective: 8 September 2026  
Applies to the CharisRemote app on iPhone and iPad.

## Who can see what you do

**The developer of CharisRemote has no access to your TV, your network, or how you use either.** We do not operate a server, account, or cloud service this app talks to — there isn't one. Pairing and remote control happen directly between your phone and your TV, over your own Wi-Fi network, and never leave it.

## What the app does on your network

CharisRemote finds and controls your Android TV / Google TV using that device's own remote-control protocol:

- **Finding your TV** uses Bonjour, a standard local-network discovery protocol. This never touches the internet.
- **Pairing** exchanges a security certificate and a one-time code shown on your TV, over an encrypted (TLS) connection. CharisRemote refuses to connect to anything outside your local network, and never connects over cellular data.
- **Remote control** — key presses, volume, typing, app launches — travels over that same local, encrypted connection.

## What the app stores, and where

Everything is stored **only on your device**:

- Your device's pairing identity (a key pair proving to your TV it's still the same app — not personal information, and never synced to iCloud)
- Your saved TVs (name, network address, last-connected time), your shortcut row, and your appearance setting
- A short, bounded diagnostic log of recent connection failures (at most 20 entries), limited to a fixed generic description — never your TV's name, network address, or anything you typed. It's only shared if you explicitly select entries and use the Share sheet yourself.

Deleting the app removes your saved TVs, shortcuts, and diagnostic log. Your device's pairing identity, like other iOS Keychain items, can outlive an app deletion — unpair CharisRemote from the TV's own settings (Settings → Remote & accessories → the paired phone → forget/unlink; wording varies by TV) to remove it from the TV's side.

The "Feedback & bug reports" link in Settings opens a webpage in your browser — the app doesn't send anything on its own when you tap it.

## What we do not do

- No sign-in, no account, no advertising ID collected by us
- No analytics or crash reports sent to the developer
- No sale or sharing of your data — we never receive it
- No third-party SDKs of any kind in the app

## The one exception: in-app purchase

CharisRemote's one-time Pro unlock is processed entirely by Apple through StoreKit. We never see or handle your payment details — see [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) for how Apple handles that transaction.

## Children

CharisRemote is not directed at children and does not knowingly collect any information from anyone, of any age — there's nothing here to collect.

## Changes

If this statement changes in a way that affects what we collect or share, we'll update the date at the top and note it in the app's release notes.

## Contact

Questions about this statement, or a bug/feature report: email **[charistools.dev@gmail.com](mailto:charistools.dev@gmail.com)** or [open an issue](https://github.com/chengguan/CharisTools/issues).

This is a plain-language description of what the app does, not legal advice.
