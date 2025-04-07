# jbig2dec : 0.20-r0

This patch is based on jbig2dec version 0.20-r0, which is available at:
https://github.com/ArtifexSoftware/jbig2dec/releases/download/0.20/jbig2dec-0.20.tar.gz

## Affected CVEs:
- CVE-2023-46361

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source jbig2dec`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
