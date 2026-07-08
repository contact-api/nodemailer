# Contact API Nodemailer

Nodemailer (SMTP) email provider for `@contact-api/core`.

[![CI](https://github.com/contact-api/nodemailer/actions/workflows/ci.yml/badge.svg)](https://github.com/contact-api/nodemailer/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](./LICENSE)

## Usage
```ts
import { createNodemailerProvider } from "@contact-api/nodemailer";
const provider = createNodemailerProvider(); // reads SMTP_CONFIG
```

## Environment Variables
| Variable | Description |
| --- | --- |
| `SMTP_CONFIG` | JSON string of SMTP settings (`host`, `port`, `auth.user`, `auth.pass`, `secure`) |

## License
MIT License - see [LICENSE](./LICENSE) for details.
