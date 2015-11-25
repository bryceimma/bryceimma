# vergelijking workflows
Met HUGO maak je zelf een static site aan de hand van layouts. De content vul je op met Markdown bestanden.

Enkele voordelen van een static site na dat de layout volledig klaar is:

1. Snel en eenvoudig nieuwe posts maken met markdown files
2. gemakkelijk uploaden via git
3. via config kan je categories en tags maken
4. al je posts in 1 map

Enkele nadelen:

1. moeilijk een layout maken
2. moeilijk je layout aanpassen naar jou wens
3. soms moeilijker om te begrijpen

Met hugo kan je dus mooie en goede blogs aanmaken en hosten op een geswenst platform.

Er zijn ook andere systemen zoals Wordpress. Deze is voornamelijk (en dus het simpelste) webbased. 

In het algemeen is een systeem als Wordpress veel gemakkelijker dan een static generator. 

Enkele voordelen van Wordpress:

1. Gemakkelijk posts maken via de website
2. post makkelijker beheren
3. layout makkelijker opmaken 
4. weinig tot geen kennis vereist

Enkele nadalen:

1. minder vrij in layout opmaak
2. je moet je plaatselijk aanmelden om iets te veranderen of een nieuwe post aan te maken
3. de gratis versie heeft een watermerk op je blog waardoor iedereen kan zien dat je het via Wordpress hebt gemaakt
4. je kan het niet zomaar hosten op je eigen server

### conclusie:

Wil je snel en eenvoudig een blog maken om bijvoorbeeld taken te delen of verslagen te publiceren, dan kan je het best houden bij een systeem als Wordpress. Wil je liever iets professioneel? Dan kan je gebruik maken van een static site. Merk wel op dat deze veel meer tijd nodig heeft om te maken, en dat enige kennis wel noodzakelijk is. 

link naar de source-repository op [Gitlab](https://gitlab.com/bryce-vandenbrande/gipsite.git "Gitlab").

link naar de repository op [github](https://github.com/bryceimma/bryceimma.github.io.git "github")

[Website](http://bryceimma.github.io "Website")

## Ovezicht van de directory-structuur

### content folder

1. content folder
2. posts
3. categories
4. Software


Ik koos deze structuur omdat hij makkelijk is om bepaalde taken te groeperen.

### layout

1. dafault
2. partials (heel belangrijk voor het maken van pagina's
3. index.html (belangrijk als basis voor pagina's)

In deze map wordt de layout van de site samengesteld. Deze files zijn gekopiëerd van het thema 'material-design'.

Het moeilijkste was de layout. Na verloop van tijd wende dit wel en begon het te lukken. Maar ook niet alles wil lukken. Bijvoorbeeld de pagina 'Over.html' heb ik handmatig moeten maken en in de public map zetten omdat ik dit niet klaar kreeg in hugo, om deze pagina te laten genereren.