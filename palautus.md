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
