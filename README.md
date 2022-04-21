# Pokédex!

![This is an image](https://oyster.ignimgs.com/mediawiki/apis.ign.com/pokemon-black-and-white/4/4e/Pok%C3%A9dex_BW.png)

## A Ruby on Rails CRUD 

Rails 7.0.2.3\
Puma version: 5.6.4 (ruby 3.1.1-p18) ("Birdie's Version")\
SQLite3

### Setup:
-Create the database and import the pokemons (/lib/seeds/pokemon.csv)
```sh
rails db:migrate
rails db:seed
``` 

-Run the server
```sh
rails server
``` 
