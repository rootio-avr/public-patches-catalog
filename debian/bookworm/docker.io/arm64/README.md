# docker.io : 20.10.24+dfsg1-1+deb12u1.aikido.4

This patch is based on docker.io version 20.10.24+dfsg1-1+deb12u1.aikido.4, which is available at:
https://sources.debian.org/src/docker.io/20.10.24+dfsg1-1+deb12u1/

## Affected CVEs:
- CVE-2024-36623
- CVE-2024-29018

## How to Apply:
1. Obtain the source package: `apt source docker.io`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
