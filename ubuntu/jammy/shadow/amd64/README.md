# shadow : 1:4.8.1-2ubuntu2.2

This patch is based on shadow version 1:4.8.1-2ubuntu2.2, which is available at:
https://launchpad.net/ubuntu/+source/shadow/1:4.8.1-2ubuntu2.2/

## Affected CVEs:
- CVE-2023-29383

## How to Apply:
1. Download the original Ubuntu source package: `apt source shadow`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
