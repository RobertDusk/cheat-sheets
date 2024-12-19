# Alembic

alembic is a database migration tool for SQLAlchemy

- [website](https://alembic.sqlalchemy.org/en/latest/)
- [github](https://github.com/sqlalchemy/alembic)

| command | description |
| --- | --- |
| `alembic init alembic` | Initialize environmnet |
| `alembic upgrade head | Upgrade database to latest revision |
| `alembic downgrade base` | Downgrade database to base |
| `alembic revision --autogenerate -m "<description>"` | Creates an automatic revision file based on sqlalchemy model |
