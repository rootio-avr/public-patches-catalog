# ffmpeg : 7:5.1.9-0+deb12u1.aikido.11

This patch is based on ffmpeg version 7:5.1.9-0+deb12u1.aikido.11, which is available at:
https://sources.debian.org/src/ffmpeg/7:5.1.9-0+deb12u1/

## Affected CVEs:
- CVE-2025-22921
- CVE-2023-49528
- CVE-2024-31578

## How to Apply:
1. Obtain the source package: `apt source ffmpeg`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `dpkg-buildpackage -us -uc`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
