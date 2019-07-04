## Getting Started

### Prerequisites

Make sure you have Git, Docker and Yarn installed before you run the script! Also make sure no other Docker containers are currently running.

Check with
```bash
$ docker ps
```

Stop any running containers
```bash
$ docker stop $(docker ps -aq)
```

### 0. Clone this repository

Please clone into directoy that is already bind with docker.

```bash
$ git clone https://github.com/AungPhyoKywe/Laravel_Guzzle.git
$ cd Laravel_Guzzle
```

### 1. Bind local directory with docker directory 

```bash
$pwd
$ docker run --rm -v ($pwd):/app composer install
```


### 2. Running project
```bash
$docker-compose up -d
```
That's it!
