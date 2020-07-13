# elixir
overview elixir language and phoenix framework

<img src ="https://raw.githubusercontent.com/ttpho/elixir/master/elixir_phoenix_framework.png" />

# PostgreSQL

1. Install 

```
brew update
brew install postgresql
```
Check installed , by version 

```
postgres --version
```

2. start and stop your Postgres database

```
pg_ctl -D /usr/local/var/postgres start
pg_ctl -D /usr/local/var/postgres stop
```

3. create/delete database 


```
createdb mydatabasename
dropdb mydatabasename
```

4. phoenix ❤️ PostgreSQL

Before you run ```mix ecto.create``` , you must be start Postgres database
