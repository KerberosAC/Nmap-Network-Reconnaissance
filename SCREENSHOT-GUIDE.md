# Screenshot identification and placement guide

All screenshots in this repository were extracted from the original **lab1 Pen Test A.Cox.docx** report, without replacing them with stock images. File names correspond to their matching README implementation steps.

| Original embedded file | Original report caption | GitHub filename | Used in README |
|---|---|---|---|
| `image2.png` | Figure 1.1 | `screenshots/01-connectivity-verification.png` | ICMP ping connectivity test |
| `image3.png` | Figure 1.2 | `screenshots/02-nmap-host-discovery.png` | Nmap host discovery (-sn) |
| `image4.png` | Figure 1.3 | `screenshots/03-syn-service-os-detection.png` | SYN, service version and OS detection (-sS -sV -O) |
| `image5.png` | Figure 1.4 | `screenshots/04-default-port-scan.png` | Default Nmap TCP port scan |
| `image6.png` | Figure 1.5 | `screenshots/05-aggressive-scan-service-identification.png` | Aggressive scan (-A) including version detection, scripts, traceroute |

**Not included:** `image1.png` was the Caribbean Maritime University logo from the cover page, not a scan or result screenshot.

## Image placement rules

Images are stored as PNG files under `screenshots/`. Keep the directory and file names exactly as supplied or edit the links in `README.md` accordingly. Renaming a different image to an existing filename without checking its content can display the wrong evidence under a section.

## Scope and interpretation

The report names an address with `/20` subnet context, but the supplied screenshots show **one target IP scanned**, not a scan of the entire CIDR range. The final scan identifies OpenSSH and Apache version strings, while **exact OS fingerprint detection remained inconclusive**. The README preserves both facts.
