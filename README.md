Stacks Bitnami:
1º) node.js
2º) Apache

Desde Bitnami nos pedia un Update del proyecto: "oliwon/bitnami (p4qvefc)". Lo hicimos y nos generó uno nuevo:
"Node.js for oliwon/bitnami (la760r8)", dejandonos tambien el antiguo: "oliwon/bitnami (p4qvefc)"

En GitHub nos creo una nueva Branche con nombre: "stacksmith/update-dockerfile-la760r8". Luego en Git tenemos tres branches:  Apache(stacksmith/add-dockerfile-avt4r0e), NodeJS-OLD(stacksmith/add-dockerfile-p4qvefc y NodeJS-NEW(stacksmith/update-dockerfile-la760r8).

Git nos pide, si queremos, que el NodeJS-NEW lo unamos (merge) con con master. Le decimos que si y entonces el master coge los cambios del NodeJS-NEW.

El propio Git nos dice que podemos borrar el NodeJS-NEW (si queremos) pues ya esta unido al master. Lo hacemos.
