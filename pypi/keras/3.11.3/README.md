# keras : 3.11.3

This patch is based on keras version 3.11.3, which is available at:
unknown

## Affected CVEs:
- GHSA-gfmx-qqqh-f38q
- AIKIDO-2026-290660
- AIKIDO-2026-480615
- CVE-2025-12060
- CVE-2025-12638
- CVE-2026-0897
- CVE-2026-11816
- CVE-2026-1462
- CVE-2026-1669
- CVE-2026-12480
- CVE-2026-12481
- CVE-2026-12484
- GHSA-28jp-44vh-q42h
- GHSA-xfhx-r7ww-5995

## How to Apply:
1. Clone or download the source code for keras
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `python -m build` or `pip install -e .`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
