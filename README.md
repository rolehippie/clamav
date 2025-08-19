# workspace

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/clamav)
[![General Workflow](https://github.com/rolehippie/clamav/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/clamav/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/clamav/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/clamav/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/clamav/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/clamav/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/clamav)](https://github.com/rolehippie/clamav/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.clamav-blue)](https://galaxy.ansible.com/rolehippie/clamav)

Ansible role to install and configure Clamav virus scanner.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [clamav_tcp_addr](#clamav_tcp_addr)
  - [clamav_tcp_socket](#clamav_tcp_socket)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### clamav_tcp_addr

Address to bind for tcp connections

#### Default value

```YAML
clamav_tcp_addr: 127.0.0.1
```

### clamav_tcp_socket

Port to bind for tcp connections

#### Default value

```YAML
clamav_tcp_socket: 3310
```

## Discovered Tags

**_clamav_**

## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
