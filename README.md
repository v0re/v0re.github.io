# v0re.github.io

Personal portfolio and tools for red team operations.

**Live site:** [https://v0re.github.io](https://v0re.github.io)

## Overview

Red Team Operator | Penetration Tester | Security Researcher at HNK7 Security

This repository contains:
- Personal portfolio website showcasing skills, experience, and tools
- Client-side security utilities (no server, no logging, no data collection)

## Structure

```
.
├── index.html          # Main portfolio page
├── tools.html          # Tools collection page
└── tools/              # Individual tools
    └── curl/           # cURL converter tool
```

## Tools

### cURL Converter
Auto-detects browser cookies & headers, converts to ready-to-run curl command.

- **Live:** [https://v0re.github.io/tools.html](https://v0re.github.io/tools.html)
- **Features:** Auto-detect cookies/headers, all HTTP methods, clipboard copy
- **Privacy:** 100% client-side, no data transmission

See [tools/README.md](tools/README.md) for more details.

## Local Development

```bash
# Clone the repository
git clone https://github.com/v0re/v0re.github.io.git
cd v0re.github.io

# Serve locally (any HTTP server works)
python3 -m http.server 8000

# Open http://localhost:8000 in your browser
```

## Privacy

All tools run entirely in your browser.
**No data is uploaded, logged, or stored.**
Closing the page clears everything.

## Tech Stack

- Pure HTML5, CSS3, JavaScript
- No frameworks, no build process
- Responsive design with modern CSS
- GitHub Pages for hosting

## License

© 2026 v0re — All engagements are authorized.

## Contact

- **GitHub:** [github.com/v0re](https://github.com/v0re)
- **Company:** [HNK7 Security](https://hnk.tw)
- **Email:** admin@hnk.tw
- **Telegram:** [@v0re](https://t.me/v0re)

---

*Built with intent. Deployed with precision.*
