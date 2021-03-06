---
layout: layout.pug
navigationTitle:  dcos edgelb template delete
title: dcos edgelb template delete
menuWeight: 130
excerpt:

enterprise: false
---

# Description
Reverts a custom config template to the default value.

# Usage

```bash
dcos edgelb template delete <pool-name>
```

# Options

| Name, shorthand | Description |
|---------|-------------|
| `--help, h`   | Print usage. |
| `--verbose`   | Enable additional logging of requests and responses. |
| `--force-insecure`   | Allow unverified TLS certificates when querying service. |
| `--custom-auth-token=DCOS_AUTH_TOKEN`   | Specify a custom auth token to use when querying a service. |
| `--custom-dcos-url=DCOS_URI/DCOS_URL`   | Specify a custom cluster URL to use when querying a service. |
| `--custom-cert-path=DCOS_CA_PATH/DCOS_CERT_PATH`   | Specify a custom TLS CA certificate file to use when querying a service. |
| `--name="<name>"`   | Name of the service instance to query. |

# Parent command

| Command | Description |
|---------|-------------|
| [dcos edgelb](/service-docs/edge-lb/1.0.0/cli-reference) |  Manage Edge-LB. |

# Examples

See the [Edge-LB Usage](/service-docs/edge-lb/1.0.0/usage).
