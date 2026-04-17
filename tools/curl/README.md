# ⚡ cURL Converter

**Live:** [https://v0re.github.io/tools.html](https://v0re.github.io/tools.html)

Automatically detects your browser's current cookies and headers, then converts them into a ready-to-run `curl` command.

## Features

- Auto-detects all cookies from the current browser session
- Captures browser headers (User-Agent, Accept, Accept-Language, Sec-Fetch-*, etc.)
- Supports all HTTP methods: GET, POST, PUT, DELETE, PATCH, HEAD, OPTIONS
- Options: include/exclude cookies, User-Agent, Referer, `-k` (insecure), `-v` (verbose)
- One-click copy to clipboard
- Fully responsive — works on desktop and mobile
- **100% client-side — no data is sent anywhere**

## How it works

```
1. Enter target URL
2. Tool reads document.cookie + navigator.userAgent + browser fingerprint
3. Builds curl command with -H flags for each header
4. Adds -b flag with all detected cookies
5. Click copy → paste in terminal
```

## Example output

```bash
curl \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64)...' \
  -H 'Accept: text/html,application/xhtml+xml...' \
  -H 'Accept-Language: zh-TW,zh;q=0.9,en;q=0.8' \
  -H 'Accept-Encoding: gzip, deflate, br' \
  -H 'Connection: keep-alive' \
  -b 'session=abc123; csrf=xyz789' \
  'https://example.com/api/data'
```

## Privacy

No data is collected, stored, or transmitted.  
All processing happens in your browser's JavaScript engine.

---

*Part of [v0re Tools](https://v0re.github.io/tools.html)*
