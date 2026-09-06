# Vitark Den for Android, direct download

Den is a work timer, built for ADHD and autistic adults. Work in your own lengths.

This is the free, directly signed Android build, for GrapheneOS and anyone
who installs apps without a store. It is the same app as the paid one on the
App Store and, when it arrives there, Google Play. There is no account, no
advertising, no analytics and nothing leaves the phone unless you turn on
encrypted sync.

The product page is [den.forgesworn.dev](https://den.forgesworn.dev/).

## Install

1. Take the `arm64-v8a` file from the latest release below. It suits
   essentially every phone sold since 2017. The other two are for older
   32-bit phones and emulators.
2. Your phone will ask once whether to permit an install from this source.
   That is Android doing its job; you can turn the permission off again
   afterwards.
3. Install over the top when a new version appears. Uninstalling first
   deletes your list, because Den keeps no copy anywhere else.

## Check what you downloaded

Every release lists the SHA-256 of each file. On the phone or a computer:

```
shasum -a 256 vitark-den-<version>-arm64-v8a.apk
```

Every build since 0.1.0 is signed with the same certificate, so an update
installs in place. Its SHA-256 fingerprint is:

```
d079b3df17bf13e507c60e40c47d934cf7046dd5b62704a238c73641d195d54e
```

## What it asks for

Notifications, vibration, an exact alarm and a foreground service, which is
what makes a cue arrive. Nothing else: no camera, microphone, location,
contacts, usage access or file storage. The release file is checked against
that list before every publish.

## Sync, if you want it

Off until you turn it on. When it is on, records are encrypted on the phone
before they go to one relay you can change, and paired with a browser or
another phone by a six-character code. Recovery words bring the same sync
back later. The privacy page says exactly what the relay can and cannot see:
[den.forgesworn.dev/privacy](https://den.forgesworn.dev/privacy).

## Support

[den.forgesworn.dev/support](https://den.forgesworn.dev/support). A real
person reads that address.
