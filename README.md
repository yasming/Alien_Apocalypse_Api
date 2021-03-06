# Alien_Apocalypse_Api

This project is a simulation of an alien apocalypse. An alien invasion is abducting humans and swapping them for evil clones that look really similar to the original person. So, in this application we can see all survivors, edit their locations, see the statics of abducted and non-abducted survivors and add new survivors .

## Prerequisites

```
Ruby >= 2.5.0
```

```
Rails >= 6.0.0
```

```
Gem >= 3.0.6
```

```
Bundle >= 1.17.3
```

```
PostgreSQL
```

### API Documentation

```
https://app.swaggerhub.com/apis-docs/yasminguimaraes/Alien_Apocalypse/1.0.0#/
```

### Getting Started

- Running application with docker: 

```
run this command in terminal: chmod +x docker-entrypoint.sh 
```

```
Uncomment lines 23 and 63 from archive: config/database.yml, because
when postgres is running in docker db host is changed
```

```
run this commands in terminal:
```

```
docker build .
```

```
docker-compose up
```

- Running application locally: 

```
Comment lines 23 and 63 from archive: config/database.yml, because
when postgres is running locally isn't necessary expose the host
```

```
run this commands in terminal:
```

```
bundle update
```

```
rails db:migrate
```

```
if want to seed the database, run: rake db:seed or rails db:seed
```

```
rails s // start the server
```

- Running application tests: 

```
run this commands in terminal:
```

```
bundle update
```

```
rspec // run the tests
```

OR

```
rails -s // run the tests
```


