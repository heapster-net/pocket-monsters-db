# Pocket Monsters Db

In this task we will create a Pokemon database, similiar to the ones you can find online. We'll need
to gather informations, populate them into database and then create Flask app that will show us all
the data.

## Preparing an environment
For this app we'll need to install Postgresql (no Docker this time ;) ) locally. You'll also need Python 3
installed on your computer.

## Gathering the data.
Create all your code in the `project` directory. We'll split it into subdirectories to separate
different parts of the app. For gathering part create subfolder `scripts` and create `import_pokemon.py`
file. This is a script that will be probably run once in the real system - just to load initial
data, that's why we put it into scripts subfolder.

From the Pokedex project import [CSV
files](https://github.com/veekun/pokedex/tree/master/pokedex/data/csv) for pokemons list, pokemon
evolutions, pokemon types, types dictionary.

Think how to put these data into postgresql, create `schema.sql` where you'll put `CREATE TABLE`
definitions based on what you have found in these files. Try to run it on database (you can use
pipes `|` or unix output forwarding `<`)

What are the relations between these tables? How can we mark them in postgresql? Update schema.sql
to reflect these relations.

# Import the data
[To be finished] Write a script that will import data from csv to your database.
