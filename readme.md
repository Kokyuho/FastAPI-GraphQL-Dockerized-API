# FastAPI-GraphQL-Dockerized-API

A simple GraphQL API developed with FastAPI, GraphQL, SQLAlchemy, Alembic, Graphene, PostgreSQL, Uvicorn and Docker. We build an API that will allow posting, mutations and queries. SQLAlchemy + Alembic is used to manage migrations, PostgreSQL + PGAdmin  all wrapped deployed in Docker/Docker-Compose.

### Install steps:
0. Python 3.9 virtual env
1. 'docker-compose run app alembic revision --autogenerate -m "New Migration"'
1. "docker-compose up" with docker-desktop running

### Endpoint:
- http://127.0.0.1:8000/graphql --> graphiQL

### GraphQL Queries:
- allPosts
- postById(postId:Int)

### GraphQL Mutations:
- createNewPost(title:"new title1", content:"new content")
