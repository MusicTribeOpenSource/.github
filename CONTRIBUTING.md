# Contributing

**There is a Creator in every human being.** Thank you for bringing yours here.

You can contribute from anywhere in the world, starting today. You don't need an invitation, an
account with us, or anyone's permission. Fork a repository, make your change, open a pull request.

## Before you start

- **Say hi first for bigger changes.** Open an issue or ask on [Discord](https://discord.gg/gS6qtuShvw).
  Someone may already be working on it, and we'd rather help you early than review a surprise.
- **Small fixes are always welcome.** Typos, docs, tests: just send them.

## Your first pull request

1. Fork the repository and create a branch for your change.
2. **Sign off every commit:** `git commit -s`. This adds a line saying you wrote the change (or have the
   right to share it) and that it can be published under the project's license. That's the whole
   agreement: the [Developer Certificate of Origin](https://developercertificate.org/). There's no
   contract to sign.
3. Open a pull request and fill in the short template. Tell us what you changed, why, and where the work
   comes from.
4. A maintainer will reply, usually within 48 hours. We review to help you land your change, not to
   gatekeep it.

## Three things we can't accept

These protect you, everyone else here, and the project itself.

1. **Someone else's code.** No proprietary firmware, leaked or decompiled source code, license keys,
   cracks, or binaries pulled out of a commercial product. Not as files, not as links.
2. **Misused brands.** You can name a product to describe compatibility ("works with Engine OS").
   You can't use other companies' logos or names to brand your work. See [TRADEMARKS.md](TRADEMARKS.md).
3. **Unwarned risk.** If your change tells people how to flash firmware, say clearly that they do it
   at their own risk.

## Making our hardware work with other software

Compatibility work is welcome, and we do it the clean way, the way projects like Samba and WINE
have done it for decades:

1. **Describe before you build.** Write down how the target behaves (protocols, USB/HID descriptors,
   boot expectations) in a `specs/` document first.
2. **Keep two hats separate.** If you have studied decompiled or proprietary material, contribute
   descriptions and specs only. The code is written by someone working from the spec or from their
   own device, never by the person who read the proprietary code.
3. **Say where it came from.** Every pull request includes one line, for example "written from the
   spec in specs/hid.md" or "from my own measurements of my own device".

## Using AI

AI tools are fine. Say so in your pull request when a large part of the change came from one, and make
sure you understand every line you submit. A maintainer has to be able to explain anything we merge.

## Your rights

You keep the copyright to what you write. Each repository's `LICENSE` file says how it's shared, and
[LICENSING.md](LICENSING.md) explains why we chose those licenses.
