# org.eclipse.jetty:jetty-project : 11.0.26

This patch is based on org.eclipse.jetty:jetty-project version 11.0.26, which is available at:
unknown

## Affected CVEs:
- GHSA-wjpw-4j6x-6rwh
- CVE-2025-11143
- CVE-2024-6763

## How to Apply:
1. Clone or download the source code for org.eclipse.jetty:jetty-project
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
