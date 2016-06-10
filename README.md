deskpro.github.io
=================

This respository contains published DeskPRO distributions and their cryptographic hashes. The layout of the respository is:

	releases/
		|- RELEASE_ID/
			|- deskpro.zip
			|- deskpro.zip.sha256
			|- release.json
		|- manifest.json

## Releases

Each release directory contains two files:

* `deskpro.zip` contain the actual DeskPRO distribution.
* `deskpro.zip.sha256` is a text file containing the sha256 checksum of the ZIP file. (Other checksums are also available in the release.json file.)
* `release.json` contains metadata about the release, such as the date, the size, the download permalink and various checksums.

## `manifest.json`

The manifest file is a summary of all releases. This is used by the DeskPRO upgrader to get a list of available builds and is how the system knows if an installation needs updating.