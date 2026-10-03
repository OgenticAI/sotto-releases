# Sotto releases

Signed builds of Sotto Gov for macOS, and the update feed the app reads.

- **Download:** the newest DMG is attached to the [`updates` release](https://github.com/OgenticAI/sotto-releases/releases/tag/updates).
- **Update feed:** `https://ogenticai.github.io/sotto-releases/appcast.xml`

Every build is signed with Ogentic AI's Developer ID (team `T6THWT9YCD`), and every entry in the feed carries an EdDSA signature the app checks before installing.

Agencies that approve builds before they reach their Macs can mirror `appcast.xml` and the DMGs on their own server, then set that address in Sotto under **Models › Software updates › Update feed**.

This repository holds release files only.
