deskpro.github.io
=================

This respository contains published DeskPRO distributions and their cryptographic hashes. The layout of the respository is:

	releases/
		|- RELEASE_ID/
			|- deskpro.zip
			|- release.json
		|- manifest.json

## Releases

Each release directory contains two files:

* `deskpro.zip` contain the actual DeskPRO distribution.
* `release.json` is info about the release. Currently this is the same data that exists in the manifest. In future we might put other information here (such as release notes etc).

## `manifest.json`

The manifest file is a summary of all releases. This is used by the DeskPRO upgrader to get a list of available builds and is how the system knows if an installation needs updating.