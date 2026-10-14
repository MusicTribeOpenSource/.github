# Contributing to Music Tribe Open Source

**There is a Creator in every human being. Our mission is to empower those who have not and cannot.**

Everyone can contribute, from anywhere, from day one. You don't need to be a member of the
organization: fork the repository, make your change, open a pull request.

## Ground rules

1. **Be excellent to each other.** See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
2. **No piracy, no leaked code.** Never commit, link to, or redistribute proprietary firmware images,
   decompiled source code, license keys, cracks or binaries extracted from a commercial product.
3. **Respect trademarks.** Naming a product to describe compatibility ("works with Engine OS",
   "CDJ-3000-compatible HID mapping") is fine. Using other companies' logos or names in project
   branding, repository names or splash screens is not.
4. **Flash at your own risk.** Any firmware-flashing instructions must include a warning.

## Clean-room protocol (interoperability work)

When your work makes our hardware compatible with third-party software:

1. **Spec first.** Describe the target behaviour (protocols, HID descriptor maps, boot expectations)
   in a `specs/` document before opening an implementation pull request.
2. **Two teams.** If you have studied decompiled or proprietary material, contribute specifications and
   behaviour descriptions only. Implementation code must come from someone working from the public
   spec or their own analysis of their own device. Nobody writes implementation code for material
   they decompiled.
3. **Provenance.** Every pull request states where the work comes from in one line, e.g.
   "written from the public spec", "from my own device analysis", "from clean-room notes in specs/…".

## Pull requests

1. Fork the repository and create a branch.
2. **Sign off every commit** with `git commit -s`. This is the
   [Developer Certificate of Origin](https://developercertificate.org/): you confirm you have the right
   to submit the work under the project's license. There is no CLA.
3. Open a pull request. Reference the spec for interoperability work, and include the provenance line.
4. A maintainer reviews it. We aim to respond within 48 hours.

## AI-assisted contributions

Say in the pull request when a significant part of the change was AI-generated. You are responsible for
understanding every line you submit, and a maintainer must be able to explain anything we merge.

## License

Each repository states its license in its `LICENSE` file. By contributing, you license your
contribution under that license. You keep the copyright to what you write.
