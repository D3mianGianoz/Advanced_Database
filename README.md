# Progetto Unito MAADB

Repository for the Advanced Database Models and Architectures (MAADB 🇮🇹) exam's projects, session 2020-2021. Developed with love ❤ by Damiano Gianotti and Lorenzo Tabasso.

#### This project is concerned with sentiment analysis: extrating text and emoij from 60000+ tweets while comparing two different DBMS solutions: MariaDB(SQL) and MongoDB(NoSQL)

## Installation

In ordert to run this project you need to valid Docker and Python installation

### Docker

We used Docker in order to setup the same envoriment om nultiple machines. To run the project, you'll first have to install Docker.

You can install Docker in several ways. If you're using Linux the best way is to install it using your favorite package manager, othwerise, visit [Docker download page](https://www.docker.com/products/docker-desktop).

Examples
```bash
# Ubuntu
sudo apt-get install docker docker-compose
```

```bash
# MacOS
brew install --cask docker
```


```powershell
# Windows (Chocolately)
choco install docker-desktop
```

After installation, verify that Docker is correclty running with

```bash
docker info
```

If you are on unix sistem you maybe need to follow this post-installation step
https://docs.docker.com/engine/install/linux-postinstall/

### Python

This entire project is developed in Python 3.7 using virtual enviroments. If you don't have Python installed on ypur machine, you first need to install python and then install all the dependencies needed for run the project.

You can install python via web visiting [Python download page](https://www.python.org/downloads/) or with your favorite package manager.

Examples
```bash
# Ubuntu
sudo apt-get install python3.7 # At least 3.7
```

```bash
# MacOS
brew install python@3.7 # At least 3.7
```


```powershell
# Windows (Chocolately)
choco install python3
```

Then, to create the virtual enviroment see this [guide](https://docs.python.org/3/library/venv.html) from official python docs.

## Usage

Execute the setup script

```bash
# On Linux and MacOS
./setup
```

```powershell
# On Windows
setup
```

Verify that is correclty running
```bash
docker ps
```

If you wanna take down the net
```bash
docker-compose down
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
