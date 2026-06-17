# org.apache.tomcat:tomcat : 11.0.9

This patch is based on org.apache.tomcat:tomcat version 11.0.9, which is available at:
unknown

## Affected CVEs:
- CVE-2025-61795
- CVE-2025-55752

## How to Apply:
1. Clone or download the source code for org.apache.tomcat:tomcat
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
