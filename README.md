# clamav

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/clamav) [![Testing Build](https://github.com/rolehippie/clamav/workflows/testing/badge.svg)](https://github.com/rolehippie/clamav/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/clamav/workflows/readme/badge.svg)](https://github.com/rolehippie/clamav/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/clamav/workflows/galaxy/badge.svg)](https://github.com/rolehippie/clamav/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/clamav)](https://github.com/rolehippie/clamav/blob/master/LICENSE) 

Ansible role to install and configure Clamav virus scanner. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [clamav_tcp_addr](#clamav_tcp_addr)
  * [clamav_tcp_socket](#clamav_tcp_socket)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

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

## Dependencies

* [rolehippie.docker](https://github.com/rolehippie/docker)

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
