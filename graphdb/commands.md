* Per avviare il container basta lanciare (dalla cartella graphdb) il seguente comando:

    `docker compose up -d`

* Arrestare il container:

    `docker compose stop`

* Neo4j Web UI:

    `http://localhost:7474/browser/`

    Username: `neo4j`

    Password: `password`

* Accedere al container:

    `docker exec -it neo4j-container /bin/bash`
    
* Accedere alla cypher shell (dal container):

    `$NEO4J_HOME/bin/cypher-shell`

* Uscire dalla cypher shell:

    `:exit`

