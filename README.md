# Telegram-desktop .deb stub package

This is a stub .deb package for telegram-desktop. It just installs the
.snap version.

This package fixes https://bugs.launchpad.net/ubuntu/+source/telegram-desktop/+bug/2000552

## Build the package

Just run

    dpkg-deb --build --root-owner-group telegram-desktop
