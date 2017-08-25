---
layout: layout.pug
title: dcos edgelb pool config
menuWeight: 5
excerpt: ""
featureMaturity: ""
enterprise: 'yes'
navigationTitle:  dcos edgelb pool config
---


# Description
View or update the config for an Edge-LB pool.

# Usage

```bash
dcos edgelb pool config <name> [<file>] [OPTIONS]
```

# Positional arguments

| Name, shorthand | Default | Description |
navigationTitle:  dcos edgelb pool config
|---------|-------------|-------------|
| `<name>`   |             |  Pool name. |
| `[<file>]`   |             |  JSON file that contains Edge-LB configuration.  |

# Options

| Name, shorthand | Default | Description |
navigationTitle:  dcos edgelb pool config
|---------|-------------|-------------|
| `--help, h`   |             |  Print usage. |
| `--verbose`   |             |  Enable additional logging of requests and responses. |
| `--force-insecure`   |             |  Allow unverified TLS certificates when querying service. |
| `--custom-auth-token=DCOS_AUTH_TOKEN`   |             |  Specify a custom auth token to use when querying a service. |
| `--custom-dcos-url=DCOS_URI/DCOS_URL`   |             |  Specify a custom cluster URL to use when querying a service. |
| `--custom-cert-path=DCOS_CA_PATH/DCOS_CERT_PATH`   |             |  Specify a custom TLS CA certificate file to use when querying a service. |
| `--name="<name>"`   |             |  Name of the service instance to query. |

# Parent command

| Command | Description |
navigationTitle:  dcos edgelb pool config
|---------|-------------|
| [dcos edgelb](/1.10/cli/command-reference/dcos-edgelb/) |  Manage Edge-LB. |

# Examples

See the [Edge-LB Quick Start Guide](/1.10/networking/edge-lb/quickstart/).