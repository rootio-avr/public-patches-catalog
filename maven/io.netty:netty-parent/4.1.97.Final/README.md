# io.netty:netty-parent : 4.1.97.Final

This patch is based on io.netty:netty-parent version 4.1.97.Final, which is available at:
unknown

## Affected CVEs:
- GHSA-xpw8-rcwv-8f8p
- CVE-2025-55163
- CVE-2025-58057
- CVE-2025-67735
- CVE-2025-24970

## How to Apply:
1. Clone or download the source code for io.netty:netty-parent
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
