# virtualenv : 20.36.1

This patch is based on virtualenv version 20.36.1, which is available at:
unknown

## Affected CVEs:
- AIKIDO-2026-674766
- AIKIDO-2026-785880
- CVE-2026-102930
- CVE-2026-102937
- CVE-2026-102925

## How to Apply:
1. Clone or download the source code for virtualenv
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `python -m build` or `pip install -e .`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
