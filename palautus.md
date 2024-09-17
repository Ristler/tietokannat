# Viikko 1

### Kysymys 1
Vastaus: 5

### Kysymys 2
Vastaus: 5

### Kysymys 3
Vastaus: ident

### Kysymys 4
Vastaus: varchar

### Kysymys 5
Vastaus: iso_country

### Kysymys 6
Vastaus: country

### Kysymys 7
Vastaus: iso_country

### Kysymys 8
Vastaus: varchar

# Viikko 2

## Yhteen tauluun kohdistuvien kyselyiden harjoitukset

### Kysymys 1
select * from goal
![screenshot](viikko2-1.png)

### Kysymys 2
kesken
![screenshot](viikko2-2.png)

### Kysymys 3
select name from airport where iso_country ="FI" order by name ASC;
![screenshot](viikko2-3.png)

### Kysymys 4
select name, type from airport where iso_country ="FI" order by type, name;

![screenshot](viikko2-4.png)

### Kysymys 5
select name from country where name like "F%";

![screenshot](viikko2-5.png)

### Kysymys 6
select name from country where name like "%F%";

![screenshot](viikko2-6.png)

### Kysymys 7
select location from game where id = 2;

![screenshot](viikko2-7.png)

### Kysymys 8
select co2_consumed from game where id = 3;

![screenshot](viikko2-8.png)


### Kysymys 9
select co2_budget from game where id = 1;

![screenshot](viikko2-9.png)

## Where-osan liitosehto harjoitukset

### Kysymys 1
select country.name AS "country name",
airport.name AS "airport name" from airport,
country where airport.iso_country = country.iso_country and airport.iso_country = "IS";

![screenshot](viikko2.2-1.png)

### Kysymys 2
select airport.name as "airport name" from airport where iso_country = "FR" and type = "large_airport"

![screenshot](viikko2.2-2.png)

### Kysymys 3
select country.name as "country_name",
airport.name as "airport_name" from country,
airport where country.iso_country = airport.iso_country and country.continent = "AN"

![screenshot](viikko2.2-3.png)

### Kysymys 4
select airport.elevation_ft from airport,
game where game.location = airport.ident and game.screen_name = "Heini"

![screenshot](viikko2.2-4.png)

### Kysymys 5
select airport.elevation_ft * 0.3048 as "elevation_m"  from airport,
game where game.location = airport.ident and game.screen_name = "Heini"

![screenshot](viikko2.2-5.png)

### Kysymys 6
select airport.name from airport, game where game.location = airport.ident and screen_name = "Ilkka"

![screenshot](viikko2.2-6.png)

### Kysymys 7
select country.name from country, airport,
game where game.location = airport.ident and airport.iso_country = country.iso_country
and screen_name = "Ilkka"

![screenshot](viikko2.2-7.png)

### Kysymys 8
kesken

![screenshot](viikko2.2-8.png)

### Kysymys 9
kesken

![screenshot](viikko2.2-9.png)

### Kysymys 10
kesken

![screenshot](viikko2.2-10.png)







