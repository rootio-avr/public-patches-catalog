# tornado : 6.5.3

This patch is based on tornado version 6.5.3, which is available at:
unknown

## Affected CVEs:
- CVE-2026-49855
- CVE-2026-82397
- CVE-2026-31958
- CVE-2026-49853

## How to Apply:
1. Clone or download the source code for tornado
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `python -m build` or `pip install -e .`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
