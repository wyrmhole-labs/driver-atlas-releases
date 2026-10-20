# Driver Atlas Beta 3.7.0

Windows PC hardware updates, diagnostics and maintenance. Beta software for the current test group.

## Install
Download DriverAtlas-Beta-3.7.0-Setup-win-x64.exe and run it. The installer includes the desktop runtime; no GitHub account or separate source folder is needed. Windows x64 is required. Hardware/vendor coverage depends on the PC and Windows version.

## Existing users
Place DriverAtlas-Beta-3.7.0.driveratlas-update.zip in your saved update folder and select Settings > About & updates > Check for application updates. Install after reviewing the offered version.

Once 3.7.0 is installed, the normal check uses GitHub first. It downloads a newer patch and verifies its signed contents before offering installation. Your saved local/network folder is preserved as an offline fallback. Check offline packages only skips internet access. A failed network check never establishes that the app is up to date. Cached downloads or a patch copied via USB can be used without internet. Internet is required to discover or download previously unavailable releases.

## Downloads and recovery
Atlas retains two verified online download ZIPs. Saved application rollback versions are separate and remain available under About & updates. Installation changes Atlas, not installed hardware drivers. The existing update-folder cleanup requires review, especially for a shared folder.

## Verification and privacy
Patches are verified using the application's public verification key. SHA256SUMS.txt provides download checksums. The installer is not Authenticode-signed; package signatures are a separate protection and do not remove Windows publisher warnings. Online app-update checks contact GitHub and its asset CDN without uploading diagnostic reports, credentials, or hardware identifiers.

## Public packaging
Developer files and tests are excluded. JavaScript is minified without public source maps. Required PowerShell/C# adapters remain readable. This is a deterrent to casual inspection, not a guarantee against reverse engineering. Stronger native-module hardening is planned before broader public release.

## Troubleshooting
Use Troubleshooting & logs to save a diagnostic report. Review it before sharing. Reports contain hardware/software context; do not post private diagnostic reports publicly.

[Download installer and patches](https://github.com/jaguilar617/driver-atlas-releases/releases)
