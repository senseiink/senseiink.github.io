# Abani Ikenna — Personal Portfolio

A personal portfolio site for Abani Ikenna, a CEH-certified penetration tester, security researcher, and Python developer with hands-on Security Operations Center (SOC) experience.

The site showcases my skills, open-source security tooling, writeups, and certifications, with a contact section for new opportunities.

## Sections

- **Home** — Landing page with availability badge, tagline, and about
- **Skills** — Offensive security, defensive/SOC, development, and infrastructure categories
- **Projects** — Featured open-source security tools
- **Writeups** — CTF walkthroughs and blog posts (coming soon)
- **Certifications** — Verifiable credentials (CEH, TryHackMe)
- **Contact** — Email and LinkedIn

## Featured Projects

| Project | Description | Repository |
| --- | --- | --- |
| PacketProbe | Real-time network traffic analyzer built with Scapy (CSV/JSON/PCAP export) | [senseiink/packetprobe](https://github.com/senseiink/packetprobe) |
| DnsDive | Subdomain enumerator using wordlist brute-force, certificate transparency, and OSINT | [senseiink/dnsdive](https://github.com/senseiink/dnsdive) |
| PortSweep | Dependency-free concurrent TCP port scanner with service detection and host discovery | [senseiink/portsweep](https://github.com/senseiink/portsweep) |
| BugsEye | Web vulnerability scanner (headers, cookies, sensitive files, XSS, SQLi, traversal) | [senseiink/bugseye](https://github.com/senseiink/bugseye) |

## Tech Stack

- HTML5, CSS3, and vanilla JavaScript — no frameworks or build tools
- Custom fonts (Jost, Hk Grotesk) served locally
- Fully responsive, keyboard accessible, with reduced-motion support

## Getting Started

The site is static and needs no build step. Open `index.html` in a browser, or run a local server:

```sh
# Python
python -m http.server 8000
```

Then visit http://localhost:8000.

## Customizing

- **Content** — Edit `index.html`: the landing/about in the header, projects in the Work section, writeups, certifications, and the contact details.
- **Styling** — Colors and spacing are defined as CSS variables at the top of `index.css` (theme accent is `--red`).
- **Email privacy** — The contact email is assembled in `index.js` and only exposed through the "Send a mail" button to avoid scraping.

## Contact

- GitHub: [senseiink](https://github.com/senseiink)
- LinkedIn: [Ikenna Abani](https://www.linkedin.com/in/ikennaabani-pentester/)

## License

All content, tools, and code in this repository are original work. Reuse with attribution.
