# Planaria & Bitcoin Docker Environment [WIP] [Alpha]
Optimized [docker](https://docs.docker.com) image of the Bitcoin SV node, [Planaria](https://docs.planaria.network) and [Planarium](https://docs.planaria.network)

## Table of Contents
- [Installation](https://github.com/mrz1836/bitcoinsv-docker#installation)
- [Maintainers](https://github.com/mrz1836/bitcoinsv-docker#maintainers)
- [Contributing](https://github.com/mrz1836/bitcoinsv-docker#contributing)
- [License](https://github.com/mrz1836/bitcoinsv-docker#license)


## Installation
**Objective:** install [Planaria & Planarium](https://docs.planaria.network) and a full [Bitcoin SV node](https://download.bitcoinsv.io/bitcoinsv/) using [docker](https://docs.docker.com)

### Install Docker via Homebrew (Mac)
```bash
$ brew cask install docker
```

_Install docker for Mac_
```
1) Open the docker application for your applications folder
2) Finish the installation of the docker desktop application
```

_Login to docker_
```bash
$ docker login
```

_Configure Docker Defaults_
```
1) Minimum of 200 gb storage
```

### Install Bitcoin SV Node

_(Optional) Start with this repository as an example project_
```bash
$ git clone git@github.com:mrz1836/docker-planaria.git
$ cd ~/docker-planaria
```

**1) Build the containers** 
```bash
$ docker-compose build 
```

**2) Run the services / containers** 
```bash
$ docker-compose up -d
```

_Turn offf the services, remove all data_
```bash
$ docker-compose down --rmi all
```

## Maintainers
Forked from: [docker-bitcoinsv](https://github.com/BitslerCasino/docker-bitcoinsv), [planaria](https://github.com/interplanaria/planaria) and [planarium](https://github.com/interplanaria/planarium)

[MrZ](https://github.com/mrz1836) - [Satchmo](https://github.com/rohenaz) - [unwriter](https://github.com/unwriter)

Support the development of this project and the development team 🙏

[![Donate](https://img.shields.io/badge/donate-bitcoin%20SV-brightgreen.svg)](https://mrz1818.com?af=docker-planaria)

## Contributing
Feel free to dive in! [Open an issue](https://github.com/mrz1836/docker-planaria/issues/new) or submit PRs.

## License
![License](https://img.shields.io/github/license/mrz1836/docker-planaria.svg?style=flat)
