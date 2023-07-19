# Protección de un programa frente a ataques de ingeniería inversa y cracking
## Resumen
En este trabajo se investigan y desarrollan diversas técnicas para combatir la piratería informática y la ingeniería inversa, con el fin de proteger programas externos previamente compilados de las manos de personas con malas intenciones.


La solución propuesta y posteriormente desarrollada consiste en un conjunto de aplicaciones diseñadas para funcionar como un sistema. Cada aplicación tiene un objetivo específico y la solución no es efectiva sin cada uno de los proyectos desarrollados.


El conjunto de aplicaciones incluye un servidor de autenticación, una aplicación para crear archivos protegidos, una interfaz gráfica y un ejecutable encargado de la protección de los programas (Stub).


En este trabajo se explican las decisiones más relevantes tomadas en el diseño e implementación de cada uno de los proyectos desarrollados. Además, se proporciona información detallada del funcionamiento y la arquitectura de la solución implementada.


En detalle, se analiza el impacto de las diferentes técnicas empleadas en el ejecutable final protegido. Se lleva a cabo ingeniería inversa tanto de forma estática, utilizando herramientas como Ghidra, como de forma dinámica, utilizando x32dbg.


En la documentación se presentan diversas técnicas, y aquellas implementadas en el proyecto son: 1. Always Online; 2. Ofuscación; 3. Aumento de la complejidad; 4. Anti-debugging; 5. Anti-dumping; 6. Encriptación y ejecución del archivo original.


También se presenta una versión del producto diseñado y modificado para facilitar la comprensión y visualización del mismo. De esta manera, se puede entender qué monitorea el proyecto y qué se consideraría un intento de ataque.


El objetivo final de este estudio e implementación es minimizar las posibles pérdidas que una empresa dedicada al desarrollo y distribución de software podría enfrentar. Esto se debe a que una vez que un archivo se distribuye a los clientes, estos pueden hacer cualquier cosa con él.

## Repositorios de los diferentes proyectos
### Stub
> https://github.com/alfman99/Stub

### Creator
> https://github.com/alfman99/Creator

### Authentication Server
> https://github.com/alfman99/ServerAuth

### Creator-GUI
> https://github.com/alfman99/CreatorDesktop

## Memoria
> pendiente...

## Articulo resumen
> pendiente...

## Nota final
> 9.5
