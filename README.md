Stacks Bitnami:
1º) node.js
2º) Apache

Dia 24/08/2016
Desde Bitnami nos pedia un Update del proyecto: "oliwon/bitnami (p4qvefc)". Lo hicimos y nos generó uno nuevo:
"Node.js for oliwon/bitnami (la760r8)", dejandonos tambien el antiguo: "oliwon/bitnami (p4qvefc)"

En GitHub nos creo una nueva Branche con nombre: "stacksmith/update-dockerfile-la760r8". Luego en Git tenemos tres branches:  Apache(stacksmith/add-dockerfile-avt4r0e), NodeJS-OLD(stacksmith/add-dockerfile-p4qvefc y NodeJS-NEW(stacksmith/update-dockerfile-la760r8).

Git nos pide, si queremos, que el NodeJS-NEW lo unamos (merge) con con master. Le decimos que si y entonces el master coge los cambios del NodeJS-NEW.

El propio Git nos dice que podemos borrar el NodeJS-NEW (si queremos) pues ya esta unido al master. Lo hacemos.

Dia 25/08/2016
Integramos con Travis-CI y hacemos el repositorio publico para que lo vea. Se añade el fichero .travis.yml

Dia 04/11/2016
Borramos p4qvefc de StackSmith

Regeneramos avt4r0e (Apache) y nos genera jq9f5rp actualizado tanto en Stack como en Git. Borramos avt4r0e en Stack pues ya tenemos jq9f5rp

Regeneramos la760r8 (Node.js) y nos genera n0crsmy actualizadotanto en Stack como en Git. Borramos la760r8  en Stack pues ya tenemos n0crsmy

Unimos el master con n0crsmy.  No unimos las otras ramas pues el Master es un Node.js y las otras Ramas son Apache
