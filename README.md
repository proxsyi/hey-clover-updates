# HeyClover update channel

This public repository is only for the Sparkle appcast and public HeyClover release artifacts. The application source remains in the private `proxsyi/hey-clover` repository and is not mirrored here.

## Release requirements

- Publish only a production HeyClover build that has been Developer ID signed and Apple notarized.
- Publish a Sparkle EdDSA-signed update archive and matching appcast entry.
- Keep automatic update checks/notifications enabled in the app; automatic download/install remains off by default.
- Never publish source snapshots, credentials, private configuration, or test builds here.

The appcast is intentionally empty until a release passes the signing and notarization checks.
