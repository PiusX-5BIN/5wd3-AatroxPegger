![JSgame](../CSS%20docs/Fotos/JSgame%20foto%201.png)

# JavaScript Game

### Home
### JavaScriptComicbook
### Superherowebsite
### GameDevelopment
### Programming

Hey, welkom bij mijn Javascript Game pagina. Hier ga ik meer uitleg geven over mijn Javascript game. Het spel dat ik had gemaakt in Javascript taal is Spaceinvader. Ik had dit spel gekozen omdat het vrij simplistisch is om te maken. Je bent de blauwe vliegtuig en u moet de rode, groene, en gele vliegtuigen neerschieten. De hoeveelheid punten die u krijgt hangt af van welk gekleurde vliegtuig. De Rode vliegtuigen geven 1 punt, De groene 2 punten en de gele 5 punten. Het doel van het spel is het kapotschieten van andere vliegtuigen en zo veel mogelijke punten te halen. Games maken in het algemeen is wel moeilijk, want je gaat veel errors krijgen omdat je ook een game voor de eerste keer niet correct gaat schrijven. Bij dit project had ik spijtig genoeg het punten systeem niet erop kunnen zetten vanwege de tijdberperking dat we hadden en ook niet wist hoe je het moest doen. Ik had ook geen /_respawn_/ methode en een /_Game Over_/ scherm in mijn game geschrijven ook omwille van de dezelde redenen. Bij elk object staat er een groene tekst helemaal boven. Dat legt uit wat het object eigenlijk doet.

Bij het maken van deze game ben ik eerst begonnen met een schets te maken in Google drawings.

![Foto2](../Fotos/JSgame%20foto%202.png)

Daaarna ben ik begonnen met het maken van 'Gameobjects'. Dat zijn de objecten van u game die met andere objecten kunnen botsen. was ik begonnen met het maken van de speler, de blauwe vliegtuig. Je kan zien dat ik de functies die ik had aangemaakt in de functie /_update_/. De /_update_/ functie zet de functies die ik had aangemaakt in een herhaling waardoor ze elke keer hetzelfde gaat doen zoals je kan zien bij /_MovePlayer_/ en /_Shoot_/. Elke keer gaat mijn laser en mijn blauwe vliegtuig frames opschuiven. Deze toepassing is overal zo. Je kan ook zien dat ik een /_consttructor_/ en een /_super_/ had staan. De /_constructor_/ geeft aan welke parameters moeten ingevuld worden om de blauwe vliegtuig te maken.

![Foto3](../Fotos/JSgame%20foto%203.png)

Dit is hoe ik de vijanden had gemaakt. Ik had 3 verschillende vijanden en deze 'Enemy' gameobject is de basis voor alle vijanden. helemaal van onder kan je zien hoe ik de automatisering van het schieten van lasers.

![Foto4](../Fotos/JSgame%20foto%204.png)

Om vijanden neer te knallen moet je ook wel lasers. De vijanden zelf hebben ook nodig. Onderaan zie je een /_OnOverlap_/. Dit legt uit wat er gebeurt zou uw of de laser een ander object raken.

![Foto5](../Fotos/JSgame%20foto%205.png) ![Foto6](../Fotos/JScomicbook%20foto%206.png)

In mijn gameclass 'SpaceInvader' zullen dan de nodige object staan. De object die je in de gameclass zet zijn de objecten die je als eerste zult zien. De nodige parameters worden pas ingevuld in de game class. De parameters, waardes die aan functies worden meegegeven, moeten in de gameobjects nooit een specifieke waarde hebben. Als je dat zou doen dan gaat de game eerst de parameters van de gameclass pakken(want dat is waar de hitbox zalstaan) en dan optellen met elke specifieke parameters dat in de gameobject staat. Bijvoorbeeld, uw hitbox staat in het midden van uw scherm maar uw vliegtuig staat helemaal rchts van het scherm wat niet klopt. Daarom dat ik bijna bij elke ingegeven parameter in de gameobjects naar de juiste parameter van zijn constructor verwijst(bv.: x,y,this.width, this.height of 0 kan ook maar kan voor problemen zorgen) om ze te centraliseren. 'Laser' en 'EnemyLaser' zijn uitzonderingen omdat ze niet in de gameclass worden vermeld en ze een deel uitmaken van een ander object.

![Foto7](../Fotos/JSgame%20foto%207.png)

Om de game nog te spelen moet je het nog verwijzen in html. Dit document was al opvoorhand gemaakt door de leerkracht want op dat moment kon ik nog geen html. De groene tekstjes vertellen wat er gedaan moest worden en niet.

![Foto8](../Fotos/JSgame%20foto%208.png)

Je kan op deze link drukken om het eens uit te proberen(LET OP: Dit gaat niet werken voor apparaten zonder toetsenbord).