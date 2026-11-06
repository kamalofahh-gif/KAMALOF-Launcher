# KAMALOF Launcher

KAMALOF is a Windows launcher for the Booster application.

## Release hosting

Publish the Booster installer/executable as a GitHub Release asset. The launcher should:
1. Check the latest published version manifest.
2. Check whether the local Booster exists and matches the expected SHA-256.
3. Download only when missing or outdated.
4. Verify SHA-256 before launching.
5. Keep the installed application in the user's normal AppData application folder.

## Current status

Repository created. Release asset and version manifest still need to be published.

Do not place credentials, personal tokens, or private user data in this repository.
