# org.apache.tomcat:tomcat : 11.0.11

This patch is based on org.apache.tomcat:tomcat version 11.0.11, which is available at:
unknown

## Affected CVEs:
- CVE-2025-61795
- CVE-2025-66614
- CVE-2026-29145
- CVE-2026-41284
- CVE-2026-41293
- CVE-2026-42498
- CVE-2026-43512
- CVE-2026-43513
- CVE-2026-43515

## How to Apply:
1. Clone or download the source code for org.apache.tomcat:tomcat
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
