# org.bouncycastle:bc-java : 1.80

This patch is based on org.bouncycastle:bc-java version 1.80, which is available at:
unknown

## Affected CVEs:
- CVE-2025-14813
- CVE-2026-0636
- CVE-2026-5598
- AIKIDO-2026-845849
- AIKIDO-2026-758882
- AIKIDO-2026-582928
- CVE-2026-13506
- CVE-2026-8763

## How to Apply:
1. Clone or download the source code for org.bouncycastle:bc-java
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
