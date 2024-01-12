# Quickhash

Inspired by the Pokemod Atlas All-In-One

## DO NOT MESSAGE ME OR OTHERS QUESTIONS ABOUT THIS REPO

## YOU ARE ON YOUR OWN

This is a very basic setup of the new stack linked up in Docker Compose.

This is NOT meant for production, purely for quick-setup tests with the UnownHash stack.

This includes:

* MariaDB database(10.11)
* Dragonite
* Dragonite-Admin
* Golbat
* Rotom
* Koji
* ReactMap(develop)

If you uncomment the cache and logs binds, create the folders first:

```console
mkdir cache logs
```

Boot up

```console
docker compose up -d
```

Once everything boots up, go to Koji admin panel <http://localhost:9100>
Make a dragonite project and add ``http://dragonite:7272/reload`` in API host and tick Scanner!
