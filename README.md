# CAuDri e.V. - Hitobito Development Server

This repository is a fork of [hitobito/developement](https://github.com/hitobito/development). For general setup instructions, refer to the [README.md](https://github.com/hitobito/development/blob/master/README.md) of the original repository.

## General 

We are using Hitobito internally for our member management. Since we are a rather small organization and rarely need to access the the server, we decided to only host the Hitobito development server locally. 
Our member database is stored in our Cloud Storage and is accessible by our board members.

## Setup

### Prerequisites

Make sure [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) are installed on your machine.

### Installation
**Note: Incomplete! Missing Database integration**

1. Clone this repository and checkout the `caudri` branch
```bash
git clone git@github.com:CAuDri/hitobito-dev.git 
git checkout caudri
```

2. Initialize the Hitobito submodule
```bash
git submodule update --init
```

3. Start the development server
```bash
docker-compose up
```
4. Wait for the server to start (this might take a couple of minutes). You can access the server at `http://localhost:3000/` in your browser.

