# TOTP Generator on Cloudflare Worker
---
## How to Use
1. Use browser: `https://totp.zikin.org/<secret>`
2. Via curl: `curl totp.zikin.org/<secret>` to get plain text without any HTML code.

e.g. https://totp.zikin.org/TOTPTEST

## Features
- The page will automatically refresh after TOTP expiration.
- Serverless

## License

This project is licensed under the MIT License.

I have referenced code from @wuzf [wuzf/2fa](https://github.com/wuzf/2fa) and the project was licensed under the MIT License.

> ref. https://github.com/wuzf/2fa <br/>
> ref. https://github.com/wuzf/2fa/blob/main/LICENSE <br/>
> ref. https://www.nodeseek.com/post-57672-1

---
## Disclaimer
This project will not store your secret. However, if you have privacy concerns, please get the source code from [this repository](https://github.com/Zikinn/totp-worker/blob/main/worker.js) and self-host it.