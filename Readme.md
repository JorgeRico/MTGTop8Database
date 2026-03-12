# Mtg Tournament Database

#### Description

````
> Utilities to process and import old access data to mysql

> Connected with potsgresql on supabasePython fastapi
> Technology: mysql + phpmyadmin
> Can be tested on docker
````

#### Container build
````
- docker-compose build
- docker-compose up -d
````

## Database dumps
````
- /dump/clean_database
- /dump/last
````

## phpMyadmnin
- [http://localhost:18081](http://localhost:18081)

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
