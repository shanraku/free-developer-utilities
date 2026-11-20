# Standards Sources and Update Policy

Primary sources are preferred over unverified lists. These links are references, not certification or endorsement.

## Primary references
- JSON: ECMA-404 — https://www.ecma-international.org/publications-and-standards/standards/ecma-404/
- JSON data interchange: RFC 8259 — https://www.rfc-editor.org/rfc/rfc8259
- Base64: RFC 4648 — https://www.rfc-editor.org/rfc/rfc4648
- URI syntax: RFC 3986 — https://www.rfc-editor.org/rfc/rfc3986
- UUIDs: RFC 9562 — https://www.rfc-editor.org/rfc/rfc9562
- SHA-256: NIST FIPS 180-4 — https://csrc.nist.gov/pubs/fips/180-4/upd1/final
- Web Cryptography API — https://www.w3.org/TR/WebCryptoAPI/
- ECMAScript specification — https://tc39.es/ecma262/

## Update policy
This is a static browser-first project. It does not currently run a hosted scheduler or silently fetch remote scripts/data. Maintainers should periodically review primary references, record the review date in relevant changes, and update implementation/documentation when standards change.

A future automated update checker may use GitHub Actions, with pinned actions, minimal permissions and no execution of untrusted content. Any automated change should be reviewed before release.

## Source transparency
Future online data features must show source attribution, direct links, retrieval time, stale-data status and fallback behavior where appropriate. Prefer multiple trustworthy sources only when they add independent value. Offline utilities should remain useful without a network connection.