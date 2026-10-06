# nodemailer : 8.0.10

This patch is based on nodemailer version 8.0.10, which is available at:
unknown

## Affected CVEs:
- CVE-2026-82659
- GHSA-2x7j-588g-ccc2
- GHSA-v53p-9fqp-m79j

## How to Apply:
1. Clone or download the source code for nodemailer
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `npm install && npm run build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
