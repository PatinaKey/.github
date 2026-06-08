# Security Policy

## Project status

PatinaKey is a **personal, experimental, open-source project** for learning and research.

> ⚠️ It is **not audited and not certified**. Do not use it to protect real assets (accounts, keys, funds) as-is. Treat it as a research prototype.

Transparency is the heart of the project: everything is public precisely so it can be examined and challenged.

## Reporting a vulnerability

If you find a flaw (hardware, firmware, or design), please report it **responsibly**:

- **Contact:** contact@patinakey.fr *(or open a private GitHub Security Advisory on the affected repository)*
- **Do not open a public issue** for an unfixed vulnerability.
- Describe the issue, its impact, and a proof of concept if possible.

Target response time: **7 days**. This is a volunteer project, so there is **no bug bounty**, but every valid report will be **credited** (unless you ask otherwise).

## Scope

- The firmware and hardware in these repositories.
- Vulnerabilities in the **TROPIC01** secure element itself are handled by [Tropic Square](https://tropicsquare.com). Please report those to them. This project tracks their disclosures and will update its guidance accordingly.

## Good practice for users

- Only run firmware you built from sources you have verified.
- In production, lock down debug access (RDP) and the bootloader.
