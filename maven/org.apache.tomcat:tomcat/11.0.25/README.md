# org.apache.tomcat:tomcat : 11.0.25

This patch is based on org.apache.tomcat:tomcat version 11.0.25, which is available at:
unknown

## Affected CVEs:
- AIKIDO-2026-255533
- AIKIDO-2026-988180
- AIKIDO-2026-822002
- AIKIDO-2026-695688
- AIKIDO-2026-143672
- AIKIDO-2026-552818
- AIKIDO-2026-118889

## How to Apply:
1. Clone or download the source code for org.apache.tomcat:tomcat
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `mvn clean package` or `gradle build`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
