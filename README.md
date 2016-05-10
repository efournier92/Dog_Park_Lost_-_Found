#Dog Park Lost and Found

I did the excersice when I first starting learning PSQL syntax. I did it mainly to practice join queries.

The challenge was to match missing dogs with their owners user plain SQL queries.

I started by generating a database called `dog_park` in the CLI, and imported the data provided to me in `schema.sql`.

#####There are two main tables I was working with:
* Dog Owners Table
  * contains the names of people and their dogs
* Found Dog Collars Table
  * contains the names of the collars in the `Lost and Found` office

#####My `joins.sql` file contains queries to answer the following questions:
1. Which collars have a known owner? Display only collars with known owners and those owners' names?
2. For which collars is there no known owner? Display only collars without known owners?
3. What collars are in our possession? Display all collars in our possession. If an owner exists for a given collar, display that also?
4. What owners do we know about? Display all owners known to us. If a collar matches that owner, display the collar also?
