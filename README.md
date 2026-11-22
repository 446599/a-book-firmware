# A Book Firmware Releases

Public distribution point for A Book firmware packages for the read-pico-4.7 board.

This repository does not contain firmware source code. Versioned binary packages, their manifest, license notices, and SHA-256 checksums are attached to GitHub Releases. GitHub's automatically generated tag archives contain only repository documentation and deployment configuration.

## Downloads

- [Firmware releases](https://github.com/446599/a-book-firmware/releases)
- [Firmware download page](https://446599.github.io/a-book-firmware/)
- [A Book reader page](https://446599.github.io/a-book/)

Each release includes a complete ZIP package and the individual images referenced by `manifest.json`. Verify `SHA256SUMS.txt` before installation. Use the A Book reader page for the supported device installation flow.

## Compatibility

Release assets identify their board, version, image roles, flash offsets, and SHA-256 digests in `manifest.json`. Do not mix images from different releases.
