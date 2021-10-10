# Small FastAPI app to try out alembic

A small FastAPI app based on the [FastAPI tutorial on SQL Databases](https://fastapi.tiangolo.com/tutorial/sql-databases/) that integrates `alembic` for database migrations.

## Start up

1. Fire `alembic upgrade head` to create a sqlite database file with tables.
2. Use `uvicorn sql_map.main:app --reload` to fire up the app.
