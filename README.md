## opensearch tutorial


### prerequisites
1. [docker](https://www.docker.com/products/docker-desktop) - Allows you to run software in controlled containers (isolated env) on your local machine.
2. [docker-compose](https://docs.docker.com/compose/install/) - A tool for defining and running multi-container Docker applications. It allows you to define a multi-container application in a single file, then spin your application up in a single command which does everything that needs to be done to get it running.
3. [python](https://www.python.org/downloads/) - Python will be used to demonstrate the capabilities of opensearch using a jupyter notebook.

## setup
1. Create a virtual python environment using venv:
```
python -m venv venv
```
2. Active the environment
```
venv\Scripts\activate
```
3. Install the required packages
```
pip install -r requirements.txt
```
4. Start up the docker containers:
```
docker-compose up
```
5. Run the jupyter notebook
```
jupyter notebook
```

