# virtualenv : 21.7.10

This patch is based on virtualenv version 21.7.10, which is available at:
unknown

## Affected CVEs:
- CVE-2026-102930
- CVE-2026-102925
- CVE-2026-102937
- CVE-2026-113722
- CVE-2026-113732
- CVE-2026-113726
- CVE-2026-113725
- CVE-2026-113776

## How to Apply:
1. Clone or download the source code for virtualenv
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `python -m build` or `pip install -e .`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
