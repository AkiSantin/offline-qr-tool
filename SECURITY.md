# Security Policy

## Sensitive Data

TOTP setup keys, recovery codes, and generated TOTP QR Codes are secrets.

Please do not include real secrets in:

- GitHub issues
- Discussions
- Pull requests
- Screenshots
- Demo videos
- Commit messages

## Recommended Use

For real TOTP setup keys, download `index.html` and open it locally. The tool is designed to avoid network requests and browser storage.

## Reporting Security Issues

If you find a security issue, please report it privately if possible. If private reporting is not available, describe the issue without including real secrets or screenshots containing real QR Codes.
