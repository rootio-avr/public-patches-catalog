# vm2 : 3.11.8

This patch is based on vm2 version 3.11.8, which is available at:
unknown

## Affected CVEs:
- CVE-2026-100721
- GHSA-7rr2-8fr3-fjqx
- CVE-2026-100722
- GHSA-9hxx-m5g2-2q3h
- GHSA-c9wr-qm7p-p6vc
- CVE-2026-93605

## How to Apply:
1. Clone or download the source code for vm2
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `npm install && npm run build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
