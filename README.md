# Free Developer Utilities

A free, open-source, privacy-first collection of browser-based developer utilities. JSON formatting, Base64 and URL encoding, UUIDs, SHA-256, timestamps, text conversion and secure random bytes.

## Privacy first
Utilities process input locally in your browser. No account, API key, application backend or data upload is required. Never paste passwords, private keys, recovery phrases, access tokens or confidential production data into online tools.

## Security notes
- UUIDs and random bytes use browser cryptographic APIs, not Math.random().
- SHA-256 is a digest, not encryption, and plain SHA-256 is not suitable for password storage.
- Clipboard and Web Crypto availability depend on browser support and secure context (HTTPS or localhost).

## Run locally
Open index.html in a modern browser, or run:
```sh
python -m http.server 8000
```
Visit http://localhost:8000.

## Sources and updates
See [docs/SOURCES.md](docs/SOURCES.md). Standards references are linked to primary sources. This static project has no background scheduler; source changes are reviewed and committed transparently rather than silently fetched.

## Contributing and license
See [CONTRIBUTING.md](CONTRIBUTING.md) and [SECURITY.md](SECURITY.md). MIT License.

Made by SUNRAKU.
