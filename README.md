# docker-registry
Host your own docker registry.

|Services           |Version    |Image                                  |
|-------------------|-----------|---------------------------------------|
|Docker registry    |2          |registry                               |
|Registry frontend  |v2         |konradkleine/docker-registry-frontend  |

## Start registry
```
docker-compose up -d
```
The user interface will be visible on `http://localhost:59151`.