# Security policy

## Supported versions

Only the **latest release** is supported: this repository keeps the newest release alone, and an installed
zomboid-manager updates itself to it (*Help → Check for updates*).

## Reporting a vulnerability

Please **do not open a public issue** for a security problem. Report it privately on GitHub:
[**Report a vulnerability**](https://github.com/reylukakozlowski/zomboid-manager-releases/security/advisories/new)
(the *Security* tab of this repository → *Report a vulnerability*). Only the maintainer sees the report.

Please include:

- the version (*Help → About*) and your Windows version;
- what an attacker could do, and the steps to reproduce it;
- whether the problem is in the installer, the update, or the program itself.

zomboid-manager is maintained by one person in their free time. Reports are answered as soon as possible; a fix
goes out as a new release, and the report is credited unless you ask otherwise.

## Scope

In scope: `zomboid-manager-win-Setup.exe` and the other files of the releases in this repository, and the program
they install. Out of scope: the Project Zomboid mods themselves, Steam, and your server.

## Checking a download

GitHub shows the SHA-256 of every release file. Compare it with `Get-FileHash <file>` in PowerShell before running
the file (only the letters' case may differ); do not run a file whose hash differs.
