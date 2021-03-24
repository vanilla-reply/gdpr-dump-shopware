# gdpr-dump-shopware

Shopware configurations for https://github.com/Smile-SA/gdpr-dump/

## Installation
- Download either
  - https://raw.githubusercontent.com/portaltech-reply/gdpr-dump-shopware/main/shopware5.yaml 
  - https://raw.githubusercontent.com/portaltech-reply/gdpr-dump-shopware/main/shopware6.yaml

  to your project.

- Start your template with something like this:

```
extends: 'shopware5.yaml'

database:
    host:     'localhost'
    user:     'user'
    password: 'password'
    name:     'databasename'
```

If you have general extensions to this template, please make pull requests or start a discussion. Thanks and happy coding.
