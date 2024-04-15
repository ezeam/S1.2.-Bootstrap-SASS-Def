# S1.2.-Bootstrap-SASS-Def
Se crea este repositorio definitivo y deja de servir el original: S1.2.-Bootstrap-SASS


Bootcamp Angular - Práctica Sprint 1- S1.2. Bootstrap&amp;SASS

                          DESCRIPCIÓ:
 
IMPORTANT: Coneixements que has de tenir per facilitar la resolució de la pràctica.
-HTML i SASS. -> sass bootstrap 5
-Bootstrap 5: Sistema de columnes + validacions
-Media queries -> Bootstrap 5 Media Queries
-Recursos para la web: https://drive.google.com/file/d/1tOVKONIA_IyQ5yr2okxW74U6C88Td1IO/view

Tingues en compte les següents consideracions. Són errors habituals en els lliuraments:
-Posar moltes etiquetes de bootstrap innecessàries als divs.
-Respectar l'estructura container -> row -> col
-L’aspecte gràfic de la web s’ha de respectar (en aquesta entrega evitarem ser creatius)
-Molts components de bootstrap necessiten que estigui carregat el fitxer js “bootstrap.bundle.min.js”
-El src de les rutes, sense espais i en minúscules
-El teu repte és construir una landing page i fer que sembli el més possible a aquest disseny:
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/d7c14b12-6ee7-42ea-b7b3-d091afb73a2a)
El disseny per a mòbil ha de quedar així:
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/445da371-7b9a-4b53-9ee0-b367ae5b9985)
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/41b15c49-6432-400c-ad60-e8bfa9dd83a4)

Indicacions per a Bootstrap:
- Fer servir sempre que es pugui els components de Bootstrap, com per exemple els botons, cards, navs, tooltips... això t'estalviarà temps i la teva web guanyarà consistència. Aquí tens els components Bootstrap ->components accordion/
- No modifiquis mai les classes dels arxius originals de Bootstrap!
- Posicionar els elements amb les classes de marges i paddings de Bootstrap. Per a projectes grans, aquesta pràctica simplifica molt els arxius CSS.
Per saber més d' -> utilities spacing de Bootstrap
- Personalitzar el tema de Bootstrap per defecte per a adaptar-ho als estils de la web que estàs creant mitjançant SASS. No fa falta crear classes noves, pots ajustar Bootstrap per a adaptar-ho a les teves necessitats: paddings per defecte, colors del tema, marges...

                                        NIVELL 1
 Exercici 1
En aquest exercici començarem per la part principal, que és el contingut que veuen els usuaris en entrar a la web:
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/6a87b740-c049-4aaf-befa-6ce2a42cf4f5)
Per a això hauràs d'implementar:
- La barra de navegació superior fixa, utilitzant el component "navBar" de Bootstrap. Recorda revisar que el menú de tipus "burger" funcioni correctament per a dispositius mòbils.
->Components navbar: https://getbootstrap.com/docs/5.0/components/navbar/
- El contingut principal, fent servir el "grid responsive" que proporciona Bootstrap per dividir la pantalla en dues columnes, a l'esquerra com pots veure està l'eslògan, la descripció i els botons, i en la columna dreta la imatge.
->Grid system:https://getbootstrap.com/docs/5.0/layout/grid/
Requisits mínims: 
- Instal·lar Bootstrap al projecte, no fer servir cdn (que és càrrega mitjançant per link, com per exemple "<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/...." rel="stylesheet" crossorigin="anonymous">").
- Fer servir component navBar de Bootstrap.
- Fer servir Grid Responsive de Bootstrap, ja que s'ha de veure bé en tauleta i mòbil.
- Modificar amb SASS, mitjançant l'arxiu creat per tu "main.scss", el color principal i secundari de Bootstrap. Utilitza aquestes variables pels color dels botons
Color principal: #5265E1
Color secundari: #FA5959.

Exercici 2
Ara toca crear la part de funcionalitats del producte que estem venent:
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/33a8793f-369c-49df-9a5d-f24296edb532)
Requisits mínims:
- L'apartat "Features", amb el text descriptiu, ha d'anar dins del Grid de Boostrap.
- Has d'utilitzar el component tabs de Bootstrap, modificant els seus estils per adaptar-los a la nostra web
- Responsive.


Exercici 3
Has de construir la tercera part de la web: l'àrea de descàrregues:
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/74a51ddd-0240-40dd-805d-2c89977690f1)
Com les cards de la imatge són molt diferents a les cards de Bootstrap, en aquest exercici et donem la possibilitat de, o bé personalitzar les cards de Bootstrap o bé crear les teves pròpies classes per maquetar-les.
Requisits mínims:
- Responsive.
- Botons de Bootstrap de color primary definit en l'exercici 1.

Exercici 4
ENHORABONA! Ja gairebé tens el nivell 1 completat! Ara toca desenvolupar l'apartat de FAQS:
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/919bb6fe-a658-4564-add9-d5189bb2eb7c)
Requisits mínims
- Fer servir el component "Accordion" i personalitzar les classes per a adaptar-lo al disseny.
- Responsive.
- Botó de Bootstrap.

                                                                    NIVELL 2
COMPTE! abans de passar al nivell 2 verifica que has entès bé tots els exercicis del nivell 1. 
El nivell 2 i 3 són opcionals, l'important és aprendre els conceptes de cada sprint, si l'has copiat ràpid d'internet no té valor, ja que si passes així tots els sprints, hauràs treballat molt i après poc. 
En una entrevista tècnica en una empresa o en les proves de nivell de l'itinerari (després del sprint 5 i 9) es detecta molt ràpid aquests casos. No retardis el teu aprenentatge, millor fer pocs exercicis bé que molts ràpids.


Exercici 5
Només falta un bloc per acabar la web: el footer.
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/d811244b-bd0d-494c-bf91-a1f4af1a4019)
Requisits mínims
- Fer servir els formularis de Bootstrap.
- Mostrar un missatge d'error quan el formulari del butlletí de notícies s'envia, i el camp d'entrada és buit o l'adreça de correu electrònic no està formatada correctament. S'ha de fer amb Bootstrap.



                                                                  NIVELL 3
Exercici 6
Modificar els estats actius dels botons, links, tabs i avisos de la web, perquè quedin així quan es passi el cursor per sobre:
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/023967d3-8049-4119-9238-cf0961114716)
![image](https://github.com/ezeam/S1.2.-Bootstrap-SASS/assets/24222710/6cb0dc84-7b1e-4259-9271-4d30d879e202)

Recordatoris
- És obligatori pujar tots els lliuraments almenys amb el nivell 1 al final de l'sprint per a poder passar al següent.
- Els lliuraments es faran a ser possible el dimecres o dijous de la segona setmana de l'sprint. 
- Com a molt tard el lliurament es farà el dilluns següent a la finalització de l'sprint, dia que comença el nou sprint.
- Si vols avançar al següent sprint abans d'hora, has de finalitzar els tres nivells de la tramesa.









