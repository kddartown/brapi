<a name="readme-top"></a>
---
# Containerization of BrAPI

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Introduction

This project aims to containerize [BrAPI (Breeding API)](https://brapi.org/), making it easier to deploy and manage BrAPI services. BrAPI is an open standard for connecting plant phenotype/genotype databases and is widely used in agriculture and ecology industries. This containerization is aligned with the mission of [Diversity Arrays Technology (DArT)](https://www.diversityarrays.com/), which aims to provide a secure, efficient platform for integrating phenotypic, genetic, and environmental data.

## Getting Started

### Prerequisites
#### Basic usage
- Docker (>= 20.x)
- Docker-Compose

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/kddartown/brapi/brapi.git
   ```
2. Navigate to the project folder:
   ```sh
   cd brapi
   ```
3. Build the Docker container:
   ```sh
   docker build -t brapi-container .
   ```

## Usage

Run the Docker container:

```sh
docker run -p 8080:8080 brapi-container
```
### Docker Compose

docker-compose up -d

## Features

- Streamlined installation and deployment of BrAPI services
- Compatibility with existing BrAPI databases
- Scalable and decentralized architecture
- Enhanced security features

### Advanced

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![Python][Python.org]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated. For contributing guidelines, please see [CONTRIBUTING.md](./CONTRIBUTING.md).
<p align="right">(<a href="#readme-top">back to top</a>)</p>
## License

Distributed under the 
<p align="right">(<a href="#readme-top">back to top</a>)</p>
## Contact

Contact Name - gavintomlins+brapi@gmail.com
Project Link: [https://github.com/kddartown/brapi](https://github.com/kddartown/brapi)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
# Acknowledgements

- [BrAPI](https://brapi.org/)
- [Diversity Arrays Technology](https://www.diversityarrays.com/)
- [Docker](https://www.docker.com/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
---
