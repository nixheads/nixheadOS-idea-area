# Misc Ideas

## Package Manager

* mechanic - keeps with the car theme implicitly set by nOS

## Guidlines for Install (this shit might get real big)

- Should have a variety of install methods:
	- Net install.
	- Physical Media Install:
		- Optical:
			- CD
			- DVD
		- Flash:
			- USB
			- Others?
- Should have a vairety of install "presets"?:
	- Minimal
	- Custom
	- Automated
	- Basic
	- "Server"?
- The Net Install shoul:
	- Be lightweight.
	- Have modular components you can load (like the Debian installer).
	- Be simple to write PXE/iPXE bootscripts for.
	- Have prebuilt isos for the community.
- Should have a framework for automated/unattended installs.
	- This framework if it can be helped should be:
		- Pre existing.
		- Stupidly simple to script for (not like Debian preseed) >.>
		- Should be generated for each isntall a person does.
	- e.g. anaconda/kickstart, Debian preeseed.
- Repos should have:
	- The repo server(s) should:
		- Be easy to navigate.
		- Have a sensible setup.
		- support a variety of protcols http(s)/rsync/ftp(s).
- Packages should:
	- Conform to a standardize compression method:
		- e.g. gz, tar, lz(4), xz, etc.
	- Not be hard to package at all (Looking at you apt...POS).
	- Have a centralized submission area for the community:
		- e.g. AUR, Ports system, etc.

