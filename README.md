# sentry-native deb package

This project contains the necessary logic for packaging the
[sentry-native](https://github.com/getsentry/sentry-native) project, resulting
in these packages:

- libsentry-dev
- libsentry0
- libsentry0-dbgsym
- sentry-crashpad
- sentry-crashpad-dbgsym

Depend on libsentry-dev for building, and libsentry0 and sentry-crashpad for
run-time.

The library is compiled with Qt support, requiring libqt5core5t64.

Binary compatibility is assumed to be the major version number (currently 0).
This has never been verified, and may not be true (i.e. 0.11.0 is not backwards
compatible with 0.10.0). If this is the case, please file an issue.

Look at FIXREF for the latest deb package for your distro.
