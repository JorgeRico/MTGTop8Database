# Mtg Tournament Database

#### Description

````
> Utilities to process and import old access data to postgresql

> Connected with potsgresql on supabasePython fastapi
> Technology: postgresql + pg-yadmin
> Can be tested on docker
````

#### Container build
````
- docker-compose up -d
````

## Database data autoload dump
````
- /data/
````

## Database last dump
````
- /dump/
````

## pg-admnin
- [http://localhost:18081](http://localhost:18081)
- PGADMIN_DEFAULT_EMAIL: admin@test.com
- PGADMIN_DEFAULT_PASSWORD: password
- create db connection (local config):
````
POSTGRES_USER: postgres
POSTGRES_PASSWORD: password
POSTGRES_DB: app_database
````

## Notes
- If you want to load a different database, add .sql file on /data/ folder


## MTG Stats project

#### Description

````
> All repositories used to develop mtg stats website

> Public development nextjs website + fastapi api    + postgresql (Supabase)
> CMS development    React website + expressjs api  + postgresql (Supabase)
> Actual Data from python scrapper (mtgtop8 website + scryfall website)
> Old data (before 2022) access old database data
````

#### Api
- [https://github.com/JorgeRico/MtgTop8Api](https://github.com/JorgeRico/MtgTop8Api)
#### Front
- [https://github.com/JorgeRico/MtgTop8React](https://github.com/JorgeRico/MtgTop8React) Reactjs
- [https://github.com/JorgeRico/MtgTop8-Nextjs-Front](https://github.com/JorgeRico/MtgTop8-Nextjs-Front) Nextjs (Actually live version)
#### BBDD
- [https://github.com/JorgeRico/MTGTop8Database](https://github.com/JorgeRico/MTGTop8Database)
#### Backoffice API
- [https://github.com/JorgeRico/MtgTop8-Backoffice-api](https://github.com/JorgeRico/MtgTop8-Backoffice-api)
#### Backoffice Front
- [https://github.com/JorgeRico/MtgTop8-Backoffice-front](https://github.com/JorgeRico/MtgTop8-Backoffice-front)
#### Python scrapper
- Supabase [https://github.com/JorgeRico/MtgTop8Scrapper-Supabase](https://github.com/JorgeRico/MtgTop8Scrapper-Supabase)
- Mysql (previous version, not full updated) [https://github.com/JorgeRico/MtgTop8Scrapper](https://github.com/JorgeRico/MtgTop8Scrapper)
- Access data to mysql [https://github.com/JorgeRico/MtgTop8AccessData](https://github.com/JorgeRico/MtgTop8AccessData)

#### Websites
- [https://mtg-stats.vercel.app/](https://mtg-stats.vercel.app/)
- [https://mtg-top8-backoffice-front.vercel.app/](https://mtg-top8-backoffice-front.vercel.app/)



#### References
- <https://hub.docker.com/>
