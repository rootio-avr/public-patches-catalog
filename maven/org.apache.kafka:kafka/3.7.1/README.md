# org.apache.kafka:kafka : 3.7.1

This patch is based on org.apache.kafka:kafka version 3.7.1, which is available at:
unknown

## Affected CVEs:
- CVE-2024-56128
- CVE-2025-27817
- CVE-2025-27818
- CVE-2026-33558
- CVE-2026-35554

## How to Apply:
1. Clone or download the source code for org.apache.kafka:kafka
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
