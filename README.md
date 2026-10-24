# ARTIQ V2 — Ubuntu releases

This repository is for ARTIQ V2 installer announcements. The application source and users' local data are not stored here.

## Install or update

1. Open the latest release from the [Releases page](https://github.com/ProNomanRizvi/ARTIQ_V2_Releases/releases).
2. Download the Ubuntu `.deb` using the Google Drive link in that release.
3. Close ARTIQ, then open the downloaded `.deb` with Ubuntu's package installer. You can also run `sudo apt install ./artiq-v2_VERSION_amd64.deb` from the download folder.
4. Launch ARTIQ from the applications menu.

The installer contains the app and browser. Ubuntu's package manager may install required system libraries from Ubuntu's repositories. Each user's ARTIQ data remains in that user's home directory during an upgrade.

## Check a download

Every release lists the exact filename and SHA-256 checksum. After downloading, run `sha256sum artiq-v2_VERSION_amd64.deb` and compare the output with the release notes before installing.

## Update notices

ARTIQ checks this repository's latest published release. If a newer version is available, the app shows an update notice linking to that release. ARTIQ does not install updates automatically.

The 2.0.7 installer has passed local tests and installation checks. Its release will be published when its final download link has been added and checked.
