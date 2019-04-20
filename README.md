# AcornMiner-Tribus HiveOS integration

From https://thefpgaforum.com/threads/tribus-solo-miner-for-acorns.87/

This miner is built for windows and linux. Give it a shot and report to the link above if it works for you. On first launch it will ask you to flash your acorns. Will take a reboot or power cycle to absorb the stand-alone flash image. This isn’t the official SQRL Miner / GPU assist magic.

## Compatible devices
Squirrels Research Labs Acorn CLE-215

Squirrels Research Labs Acorn CLE-215+

## Prerequisites
Driver available at http://www.squirrelsresearch.com/get-started-acorn/

PCIe capable M.2 slot(s) (preferably with high power design)

## Supported control keys

	- `q` gracefully stops devices and exits
	- `1`-`9` selects the appropriate worker to be targeted by commands
	- `a` selects all workers to be targeted by commands
	- `-` decreases the clock of targeted worker(s)
	- `+` increases the clock of targeted worker(s)

### Control keys with experimental features

	- `e` enables the targeted worker(s)
	- `d` disables the targeted worker(s)
	- `t` enables the tuning of targeted worker(s) for the highest stable clock.
        Not recommended to use without supervision
	- `i` helps identifying the targeted worker(s)

## Notes
Acorns can run at a max of 125C before thermal shut down, and 110C for an extended period of time (keep it <100C just to be safe)

## Exmaple Flight Sheet
Coming soon
