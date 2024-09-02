<p align="center">
  <img src="https://img.icons8.com/?size=512&id=55494&format=png" width="20%" alt="DWELLFI-ASSIGNMENT-logo">
</p>
<p align="center">
    <h1 align="center">DWELLFI-ASSIGNMENT</h1>
</p>
<p align="center">
		<em>Built with the tools and technologies:</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
	<img src="https://img.shields.io/badge/Docker-2496ED.svg?style=flat&logo=Docker&logoColor=white" alt="Docker">
	<img src="https://img.shields.io/badge/FastAPI-009688.svg?style=flat&logo=FastAPI&logoColor=white" alt="FastAPI">
</p>

<br>

#####  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Getting Started](#-getting-started)
    - [ Prerequisites](#-prerequisites)
    - [ Installation](#-installation)
    - [ Usage](#-usage)
---

##  Overview

<p> This FastAPI application provides a RESTful API with various endpoints for performing database operations, health checks, and versioning. The application includes CORS middleware for handling cross-origin requests and uses API key-based authentication for security.</p>

---

### Features

- FastAPI Based Authentication
- Docker Image support


---

##  Repository Structure

```sh
└── Dwellfi-assignment/
    ├── Dockerfile
    ├── README.md
    ├── app
    │   ├── __init__.py
    │   ├── classes
    │   └── main.py
    └── requirements.txt
```

##  Getting Started

###  Prerequisites

**Python**: `version 3.10.12`

###  Installation

Build the project from source:

1. Clone the Dwellfi-assignment repository:
```sh
❯ git clone https://github.com/mohit-217/Dwellfi-assignment
```

2. Navigate to the project directory:
```sh
❯ cd Dwellfi-assignment
```

3.1 Install the required dependencies:
```sh
❯ pip install -r requirements.txt
```
3.2 Or build the docker image :
```sh
❯ docker image build -t dwellfi-app .
```

###  Usage

To run the project using uvicorn change .classes to classes and run below command:

```sh
❯ uvicorn main:app
```

To run the project using Docker Run the below command
```sh
❯ docker container run --publish 8080:8080 --name dwellfi-app-container dwellfi-app
```



