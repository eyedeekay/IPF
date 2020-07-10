Invisble-Internet Enabled Skeleton Install Media
================================================

This is a work-in-progress install media for an I2P-based Linux distro, which I
personally do not have the time time to properly maintain for mass distribution
as an ISO. If you intend to use it, be aware of it's unfinished state. I highly
recommend forking the repository, making your desired distro-wide changes, and
then re-building the ISO. You can easily do this on a system configured with
Debian's live-build tools using the commands:

		sudo lb clean
		lb config
		sudo lb build

