# Docker image with presidents database

This postgres image is already pre-filled for educational usage on Fontys Venlo in Database course. 

Usage:

```bash
docker run -d -p 5432:5432 --name dbs1 socke77/postgresdb-president
```

- Default username is `postgres`
- Default password is `mypassword`
- Default database is `postgres`