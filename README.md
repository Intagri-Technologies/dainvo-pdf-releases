# Dainvo PDF releases

This repository distributes Dainvo PDF installers and release notes. Application source is maintained separately in a private repository.

No installers have been published yet. Release automation is configured separately and remains disabled until execution is authorized.

## Distribution formats

- macOS: universal Apple silicon and Intel packages, configured for Developer ID signing and Apple notarization.
- Windows: x64 MSI and portable ZIP, configured for Microsoft Azure Artifact Signing.
- Linux: x64 AppImage, DEB, RPM and tar archives, with signed checksums.

A release must pass validation before publication. Configuration alone does not establish that a package has passed those checks.

Download installers from [Releases](https://github.com/Intagri-Technologies/dainvo-pdf-releases/releases). GitHub's automatically generated source archives contain only this distribution repository's documentation, not the application source or installers.
