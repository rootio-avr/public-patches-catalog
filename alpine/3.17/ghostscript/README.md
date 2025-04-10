# ghostscript : 10.01.2-r0

This patch is based on ghostscript version 10.01.2-r0, which is available at:
https://github.com/ArtifexSoftware/ghostpdl-downloads/releases/download/gs10012/ghostscript-10.01.2.tar.gz

## Affected CVEs:
- CVE-2024-33871

## How to Apply:
1. Obtain the APKBUILD file and source code: `apk source ghostscript`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `abuild -r`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
