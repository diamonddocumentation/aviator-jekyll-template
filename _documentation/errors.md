---
title: ZAP API Clients
position: 3
parameters:
  - name:
    content:
content_markdown: |-
 
A summary of the clients available:

| **Language** | **Download links** | **Notes** |
|:-------------|:-------------------|:----------|
| Java         | [GitHub](https://github.com/zaproxy/zaproxy/releases) | Official API  |
| Python       | [PyPI](https://pypi.python.org/pypi/python-owasp-zap-v2.4) | Official API  |
| Node.js      | [NPM](https://www.npmjs.org/package/zaproxy) | In process of becoming an official API |
| PHP          | [GitHub](https://github.com/yukisov/php-owasp-zap-v2) [Packagist](https://packagist.org/packages/zaproxy/php-owasp-zap-v2)  | In process of becoming an official API |
| Ruby         | [GitHub](https://github.com/SUSE/owasp_zap) |           |
| Ruby         | [GitHub](https://github.com/vpereira/owasp_zap) |           |


  All errors will return JSON in the following format:
left_code_blocks:
  - code_block: |-
      {
        "error": true,
        "message": "error message here"
      }
    title: Response
    language: json
right_code_blocks:
  - code_block:
    title:
    language:
---