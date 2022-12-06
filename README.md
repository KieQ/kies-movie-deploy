# kies-movie-deploy
The deploy repository for movie

## Env
#### Online
|name|note|
|---|---|
|MOVIE_DB_POSTGRES_URL|URL to movie db|
|BACKEND_PORT|The port uesed by backend|
|TMDB_APP_KEY|The AppKey of TMDB|
|JWT_SECRET_KEY(optional)|The JWT signed key|


#### Raspberry
|name|note|
|---|---|
|VOLUMES_LOCATION|The location for backend and frontend to write and read the media file|
|TMDB_APP_KEY|The AppKey of TMDB|
