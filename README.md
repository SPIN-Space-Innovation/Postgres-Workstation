# SPIN Postgres workstation
SPIN's workstation for Postgresql database.

# Requiremets
- [Docker](https://www.docker.com/)

# Building
```sh
POSTGRES_VERSION=${Version} POSTGRES_USER=${username} POSTGRES_PASSWORD=${password} docker compose up
```

# Notes
Keep in mind that this workstation will place data folders inside this folder.