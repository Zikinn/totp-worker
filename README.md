# TOTP Generator on Cloudflare Worker
---
### How to Use:
1. Use browser: `https://totp.zikin.org/<secret>`
2. Via curl: `curl totp.zikin.org/<secret>` to get plain text without any HTML code.

e.g. https://totp.zikin.org/JBSWY3DPEHPK3PXP

### Feature
- The page will automatically refresh after TOTP expiration.
- Serverless

---
> ### Disclaimer: 
> This project will not store your secret. However, if you have privacy concerns, please get the source code from [this repository](https://github.com/Zikinn/totp-worker/blob/main/worker.js) and self-host it.
