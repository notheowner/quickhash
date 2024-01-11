# quickhash
Inspired by the Pokemod Atlas All-In-One

## DO NOT MESSAGE ME OR OTHERS QUESTIONS ABOUT THIS! YOU ARE ON YOUR OWN!!

This is an extremely basic setup of the new stack linked up in Docker. 

This is NOT for production, purely a quick test setup for understanding the workflow of the stack.

This includes:

* MariaDB database
* Dragonite
* Dragonite-Admin
* Golbat
* Rotom
* Koji
* ReactMap


docker compose up -d

Once everything boots up, go to Koji admin panel http://localhost:9100
make a dragonite project and add ``http://dragonite:7272/reload`` in API host and tick Scanner