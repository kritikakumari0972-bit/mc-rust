# MC Rust Edition — fork status

This repository is a community-maintained fork of [horizon-rust/horizon](https://github.com/horizon-rust/horizon).
The current game target is Minecraft: Java Edition 26.3. The game engine, launcher architecture, upstream work,
and original contributor history are retained under the repository's MIT licence and notices.

## What this fork milestone changes

- Gives the launcher its own visible name: **MC Rust Edition**.
- Uses MC Rust Edition branding in the window title, Home view, Windows installer metadata and Linux launcher entry.
- Keeps upstream binary names, crate names, internal Horizon identifiers, data directories, environment variables,
  and registry identity stable where they are compatibility-sensitive.
- Keeps the upstream MIT licence and contributor attribution. This fork does not claim authorship of inherited code.

## Release and update status

The launcher release source in `launcher/src/backend.rs` still points to `horizon-rust/horizon`. This is deliberate
for now: the trusted Ed25519 public key in `crates/horizon-release-sign/release-keys.txt` belongs to upstream's
release channel, and this fork does not possess upstream's private signing key. The launcher and game correctly refuse
archives that are not signed by a trusted key. Do not remove or bypass that verification to make unsigned fork
archives install.

Before switching the updater to this repository, set up an independent signing channel:

1. Generate a new Ed25519 release key for this fork. Keep its private key out of Git.
2. Add the matching public key to `crates/horizon-release-sign/release-keys.txt`.
3. Store the base64-encoded private PKCS#8 key as `RELEASE_SIGNING_KEY` in this repository's GitHub Actions
   `release` environment.
4. Verify that the fork's game and launcher workflows can build, sign, publish and verify a release end to end.
5. Only then change the launcher release repository constant and release documentation links to this fork.

Until that is done, the launcher continues to receive valid signed upstream builds. To test a game binary built from
this fork, use the launcher's **Import a game build…** flow. Imported binaries are kept separate and are not silently
replaced by the updater.

## Compatibility choices

The Rust engine and launcher have many existing `horizon-*` crate names, paths, CLI names and environment variables.
They are intentionally preserved during this branding milestone so saved installations and tooling are not broken.
The upstream visual icon is also retained for now; an original MC Rust Edition icon can be introduced in a later UI
milestone.
