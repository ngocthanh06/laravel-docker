
# Laravel Docker

### Multiple Projects:
#### Construct folder
```bash
|--laravel-docker
|--project-1
|--project-2
.
.
.
|--project-n
```
#### Setup
- Copy `.env` to `.env.example` 
- Run command
```bash
docker-compose up -d nginx workspace mariadb
```
if you use `mysql` or `postgres` then just run docker for `mysql`, `postgres`

- Copy from `laravel.conf.example` to `project-1.conf` and `project-2.conf` if there are many projects.

- Add the domains to the hosts files.
```bash
127.0.0.1  project-1.test
127.0.0.1  project-2.test
```
