# ffmpeg : 7:4.4.2-0ubuntu0.22.04.1

This patch is based on ffmpeg version 7:4.4.2-0ubuntu0.22.04.1, which is available at:
unknown

## Affected CVEs:
- CVE-2024-7055

## How to Apply:
1. Download the original Ubuntu source package: `apt source ffmpeg`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
