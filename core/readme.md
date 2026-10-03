
# ValleHack Core

**The engine behind ValleHack educational cybersecurity environments.**

ValleHack Core provides the infrastructure required to deploy, manage, update, and run containerized cybersecurity learning environments. It is designed for educators who want to deliver reproducible hands-on training without requiring dedicated laboratory hardware.

## Overview

ValleHack Core is not a collection of challenges or vulnerable machines.

Instead, it provides the platform that allows educational scenarios to be installed and executed. Learning content is distributed through independent scenario packages.

## Features

* Scenario deployment and lifecycle management.
* Docker and container orchestration.
* RootTheBox integration.
* Scenario version control.
* Automated updates.
* Cross-distribution compatibility.
* Reproducible laboratory environments.
* Support for online and in-person learning.

## Architecture

```text
ValleHack
│
├── Core
│   ├── Scenario Manager
│   ├── Update Manager
│   ├── Container Manager
│   └── RootTheBox Integration
│
└── Scenarios
    ├── Valle del Jerte
    ├── Game of Thrones
    ├── Outlander
    └── Custom Scenarios
```

## Educational Objectives

ValleHack Core enables the creation of practical learning environments for:

* Ethical Hacking
* Vulnerability Assessment
* Digital Forensics
* Incident Response
* Secure Deployment
* System Hardening
* Network Security
* Capture The Flag (CTF) Activities

## Requirements

* Linux operating system
* Docker Engine
* Docker Compose
* Git

## Installation

Installation instructions will be provided in future releases.

## Scenario Support

ValleHack Core does not include learning content.

Learning content is delivered through scenario packages that may contain:

* RootTheBox challenges
* Docker containers
* Story-driven missions
* Documentation
* Learning activities
* Assessment resources

## Contributing

Educators and cybersecurity professionals are encouraged to contribute new scenarios, improvements, and educational resources.

## License

See the LICENSE file for licensing information.

## Author

Francisco Javier Rufo Mendo

IES Valle del Jerte
