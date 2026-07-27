# gss-ntlmssp : 0.7.0-4build4.aikido.5

This patch is based on gss-ntlmssp version 0.7.0-4build4.aikido.5, which is available at:
https://sources.debian.org/src/gss-ntlmssp/0.7.0-4build4/

## Affected CVEs:
- CVE-2023-25565
- CVE-2023-25564
- CVE-2023-25563

## How to Apply:
1. Obtain the source package: `apt source gss-ntlmssp`
2. Apply the patch: `patch -p1 < diff.patch`
3. Build the package: `debuild -b -uc -us`

## License:
This patch is provided under GPLv3, in compliance with the original license of the package.
The full GPLv3 license can be found at: https://www.gnu.org/licenses/gpl-3.0.txt
