# nemo-dropbox
Updated nemo-dropbox debian package for Ubuntu 24.04 without the broken libappindicator1 dependency.

appindicator1 is no longer available as a package on later builds of Ubuntu and has been replaced by libayatana-appindicator3-1, this works perfectly with nemo-dropbox and the deb just needed a dependancy tweek.

Provided here for anyone who has been frustrated by this not being resolved.

Just download the release deb package and install as per normal with dpkg:

sudo dpkg -i nemo-dropbox_4.6.1-appindicator3-1.deb
