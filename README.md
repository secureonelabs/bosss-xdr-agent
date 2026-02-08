<p align="center">
    <img width="640px" src="logo.png" alt="BOSSS XDR Agent"/>
</p>

# BOSSS XDR Agent

> Based on [Wazuh Agent](https://github.com/wazuh/wazuh-agent), an open source endpoint security agent.

> [!NOTE]
> **Work in progress:** This project is currently under development.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [3rd Party Software Used](#3rd-party-software-used)
4. [License](#license)

## Introduction

BOSSS XDR Agent is a lightweight and versatile security monitoring component designed to run on endpoints, collecting and forwarding security-related data to the BOSSS XDR Server through an encrypted and authenticated channel.

This repository contains the BOSSS XDR Agent, a key component in the BOSSS XDR solution. The agent is deployed on monitored systems to collect data, which is then sent to the BOSSS XDR Server for analysis.

## Installation

To install the BOSSS XDR Agent, follow the steps below:

1. Clone the repository:
    ```bash
    git clone https://github.com/secureonelabs/bosss-xdr-agent.git
    cd bosss-xdr-agent
    ```
2. Use one of the following options:

    - [Build from sources](docs/dev/build-sources.md)
    - [Build packages](docs/dev/build-packages.md)
    - [Build a Docker container image](docs/dev/build-image.md)

For more detailed installation instructions, please refer to the [documentation](https://documentation.wazuh.com).

## 3rd Party Software Used

This project uses the following third-party software:

| Software | Description | License | Version |
| --- | --- | --- | --- |
| [Boost Asio](https://www.boost.org/doc/libs/release/doc/html/boost_asio.html) | Cross-platform C++ library for network programming | Boost Software License 1.0 | 1.85.0 |
| [Boost Beast](https://www.boost.org/doc/libs/release/libs/beast/) | Library built on Boost Asio for HTTP and WebSocket communication | Boost Software License 1.0 | 1.85.0 |
| [nlohmann-json](https://github.com/nlohmann/json) | JSON parsing and serialization library for C++ | MIT License | 3.11.3 |
| [OpenSSL](https://www.openssl.org/) | Toolkit for SSL/TLS protocols | Apache 2.0 and OpenSSL License | 3.3.2 |
| [sqlite3](https://sqlite.org/) | Self-contained SQL database engine | Public Domain | 3.45.0 |
| [spdlog](https://github.com/gabime/spdlog) | Fast C++ logging library | MIT License | 1.14.0 |

## Security

If you discover a security vulnerability, please send an email to security@secureonelabs.com.

## License

This project is licensed under the [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html) License.

## Attribution

This project is based on [Wazuh Agent](https://github.com/wazuh/wazuh-agent). See [ATTRIBUTION.md](ATTRIBUTION.md) for details.

Copyright (C) 2024, Wazuh Inc.
Copyright (C) 2024, SecureOneLabs
