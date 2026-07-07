# tornado : 6.2

This patch is based on tornado version 6.2, which is available at:
unknown

## Affected CVEs:
- CVE-2024-52804
- CVE-2025-47287
- CVE-2026-35536
- CVE-2026-49853
- CVE-2026-49855
- GHSA-w235-7p84-xx57
- GHSA-78cv-mqj4-43f7
- GHSA-753j-mpmx-qq6g
- GHSA-qppv-j76h-2rpx
- CVE-2023-28370

## How to Apply:
1. Clone or download the source code for tornado
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `python -m build` or `pip install -e .`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
