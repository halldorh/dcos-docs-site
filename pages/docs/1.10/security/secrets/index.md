---
layout: layout.pug
title: Secrets
menuWeight: 40
excerpt: ""
featureMaturity: ""
enterprise: 'yes'
navigationTitle:  Secrets
---

Use the Enterprise DC/OS Secret Store to secure sensitive information like database passwords, API tokens, and private keys. Storing secrets in secret paths allows you to restrict which services can retrieve the value.

[Authorized Marathon services](/1.10/overview/security/spaces/) can retrieve the secrets at deployment and store their values under environment variables.

In addition, the [Secrets API](/1.10/security/secrets/secrets-api/) allows you to [seal](/1.10/security/secrets/seal-store/)/[unseal](/1.10/security/secrets/unseal-store/) and [reinitialize](/1.10/security/secrets/custom-key/) the Secret Store.

You can also find information about secrets in the [Permissions Reference](/1.10/security/perms-reference/#secrets) section.