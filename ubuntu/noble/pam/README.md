# pam : 1.5.3-5ubuntu5.1

This patch is based on pam version 1.5.3-5ubuntu5.1, which is available at:
https://launchpad.net/ubuntu/+source/pam/1.5.3-5ubuntu5.1/

## Affected CVEs:
- CVE-2024-10963
- CVE-2024-10041

## How to Apply:
1. Download the original Ubuntu source package: `apt source pam`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
