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
	- Have prebuilt netinstall isos/images for the community.
- Should have a framework for automated/unattended installs.
	- This framework if it can be helped should:
		- Be pre existing.
		- Stupidly simple to script for (not like Debian preseed) >.>
		- Should be generated for each isntall a someone does.
		- support both GUI and Ncurses/CLI interfaces?
	- e.g. anaconda/kickstart, Debian preeseed.
- Repos should:
	- The server(s) should:
		- Be easy to navigate.
		- Have a sensible setup.
		- support a variety of protcols http(s)/rsync/ftp(s).
	- Packages should:
		- Conform to a standardize compression method:
			- e.g. gz, tar, lz(4), xz, etc.
		- Not be hard to package at all (Looking at you apt...POS).
		- Have a centralized submission area for the community:
			- e.g. AUR, Ports system, etc.

- Things I don't think, but may be good?
	- Shouldn't contain software that wants to do everything itself:
		- e.g. systemd, pulseaudio, emacs (it's almost an OS :P)
	- One application has one function, and does it DAMN well.
