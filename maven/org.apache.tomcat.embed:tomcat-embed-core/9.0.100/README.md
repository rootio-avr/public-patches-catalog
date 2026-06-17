# org.apache.tomcat.embed:tomcat-embed-core : 9.0.100

This patch is based on org.apache.tomcat.embed:tomcat-embed-core version 9.0.100, which is available at:
unknown

## Affected CVEs:
- CVE-2025-66614
- CVE-2025-31651
- CVE-2025-31650
- CVE-2025-49124
- CVE-2025-55752
- CVE-2026-24734

## How to Apply:
1. Clone or download the source code for org.apache.tomcat.embed:tomcat-embed-core
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
