# FASTAPI INTRODUCTION

**FastAPI, PostgreSQL, Async SQLAlchemy, Async requests with AIOHTTP**

## Dependecies

* Docker
* Docker-compse
* Python >= 3.6
* Pipenv

## How to run

Add project path at `PYTHONPATH` variable in `.env` file.

Start **postgres** database and **pgadmin**

```shell
docker-compose up -d
```

Start environment

```shell
pipenv shell
```

Install python dependencies

```shell
pipenv install
```

Start application

```shell
uvicorn main:app --port 8080
```

https://www.youtube.com/watch?v=1CZZAhwqyco
