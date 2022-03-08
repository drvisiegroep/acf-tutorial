# acf-tutorial
## My-first-extra-veld

Als je je wordpress in het Nederlands hebt staan wordt ACF vertaald naar 'Extra Velden'. Dus dat gaan we vandaag doen. Een extra veld aanmaken. Niets meer, niets minder. Gewoon een veldje maken wat er net nog niet was. Maar zometeen wel. Deze tutorial heeft niet bijzonder veel om het lijf en is bedoeld als een simpel voorbeeld waarop je ACF zou kunnen gebruiken. Als het goed is kan je deze tutorial gewoon volgen op de gratis versie van ACF. Dus start je server en laad je Wordpress site met ACF geïnstalleerd want 'hier wie go!'

We gaan proberen het voor elkaar te krijgen een bannerafbeelding te laten zien die we per pagina aan kunnen passen. Dus tsel je maakt een pagina aan in wordpress, dan kunnen we daar een plaatje bij plakken die dan als bannerafbeelding gebruikt gaat worden.


![image](https://user-images.githubusercontent.com/78969608/157193503-258f3b12-a98b-4ad0-8d38-dd036973a37e.png)

Kijk gerust even door alle opties en knopjes en weetikveelwat ACF allemaal voor moois te bieden heeft. En als je zover bent dan gaan we onze eerste [groep](https://www.advancedcustomfields.com/resources/group/) aanmaken door op de bovenstaande knop te klikken. Een groep is een manier om onze rotzooi wat te organiseren. Dus stel je voor ik ga allemaal spannende dingen doen met die bannerafbeelding die we zo gaan maken dan zouden we deze groep banner kunnen noemen en daar al onze velden onderbrengen die betrekking hebben op onze banner. Maar voor nu doen we het mooi rustig aan en beginnen we met 1 veld in onze groep.  
  
  
  
![image](https://user-images.githubusercontent.com/78969608/157193682-2caaa8a2-74d1-4506-9cf0-8f4043cdb600.png)

Nu moeten we gaan bepalen waar we ons extra veld willen laten zien. We hebben... Ik bedoel IK heb bepaald dat we een bannerafbeelding gingen maken op een pagina. Dat betekent dus dat we moeten gaan uitzoeken hoe we een extra veld te zien krijgen op de editor van een pagina. 

![image](https://user-images.githubusercontent.com/78969608/157193580-fef0abde-f786-451e-a6eb-4f1cc4a17f11.png)


![image](https://user-images.githubusercontent.com/78969608/157193858-eaa876c1-d2fe-4eb0-89af-569ae777885d.png)

Hier komt wat Wordpress kennis om de hoek kijken. Je moet namelijk weten dat een pagina een [post type](https://wordpress.org/support/article/post-types/) is. Laat voor nu maar even de boel de boel en neem maar aan dat de post type gelijk moet zijn aan een pagina. Hiermee verschijnt zometeen ons eerste veld op magische wijze in de editor van een pagina die we aanmaken.

![image](https://user-images.githubusercontent.com/78969608/157193909-3cbe1557-6252-4b15-9458-4c7d3b6473c8.png)

Geef voor de volledigheid de groep even een naam. Iets in de zin van: 'Mijn eerste mooie bannerafbeelding groep ding' Of een naam die meer van toepassing is. Verzin maar iets. Als je hem maar weer kan vinden. En dan gaan we een veld aanmaken. Klik maar op +nieuw veld.
![image](https://user-images.githubusercontent.com/78969608/157194101-efcacf7f-76fb-4a53-a890-22c8d01a54ca.png)
Opties? Yup, weer opties. Meer onduidelijke lijsten vol met opties waar we nog niets vanaf weten. Maar op het eerste gezicht spreken de meeste waarschijnlijk wel voor zich. Kijk ze bij gelegenheid maar rustig door en probeer te raden waar ze voor zijn. Wij willen graag een afbeelding plaatsen op onze pagina dus kiezen we voor...

Ja precies.

![image](https://user-images.githubusercontent.com/78969608/157194311-e8b29b8e-576d-4914-87da-2c81f0eb8680.png)
OH MAY GAWD! NOG MEER OPTIES! Inderdaad, wen er maar aan... Dit lijkt in het begin misschien wat overweldigend maar hoe vaker je hiermee gaat knutselen hoe handiger je er mee om kan gaan. Het eerste veld is om de beschrijving te geven aan het veld dat we gaan gebruiken. Het tweede veld (veld naam) is een belangrijk veld. Hiermee gaan we later ons veld in de code ophalen. Deze naam wordt altijd gebruikt om onze velden aan te spreken. Hierdoor weet ACF wat we bedoelen als we die aanroepen in de code. 

Dan is er nog een belangrijke optie die we niet moeten vergeten en dat is hoe we onze output willen weergeven. Wij willen graag alles lekker simpel houden. Dus hoe krijgen we normaal gesproken een plaatje op een HTML pagina? Door een URL met een plaatje in een img tag te drukken. Waarom moeilijk doen als het makkelijk kan? We kiezen hier om de URL van ons plaatje door te geven.
De rest van de opties laten we voor wat ze zijn. Maar speel er mee als je er feeling voor wil krijgen wat ze nou eigenlijk doen.


![image](https://user-images.githubusercontent.com/78969608/157289641-ec802dc6-b8b0-43cf-b151-7caaa8163bd6.png)

En dan nu het ALLER ALLERBELANGRIJKSTE! Niet vergeten te saven. Anders moeten we weer alles opnieuw doen en we zijn druk en hebben meer te doen. 

![image](https://user-images.githubusercontent.com/78969608/157194474-72e58542-cdc3-4b65-899a-a9775d4dade4.png)
Ok klaar. Je hebt je eerste veld gemaakt. Mooi toch. Lekker veldjes maken. Hoe voelt dat nou? Beetje tevreden? Alles wat je ervan had verwacht? Wat? Nee? Sommige mensen zijn ook nooit tevreden. Ok dan gaan we nog even door. We hebben dus net ons veldje aangemaakt en toen hebben we ACF verteld dat we ons veldje graag willen zie op een pagina. Dus daar gaan we dan maar naar kijken of ACF ook alles doet wat 'ie beloofd. En waarsachtig er staat nu onderaan in de editor voor een pagina een veld wat er normaal niet staat. En het is ook nog een veld waar we een afbeelding kunnen selecteren. Mooi man!


![image](https://user-images.githubusercontent.com/78969608/157194527-bc25e9d5-16b6-484e-b00f-7f5497c22e44.png)
Dan gaan we nu een plaatje uitkiezen. Gewoon een willekeurig plaatje waarvan jij denkt dat het een mooie bannerafbeelding zou zijn. Hoeft niet perse een capibara te zijn, maar waarom zou je in godsnaam iets anders als bannerafbeelding willen? Wat? Je bent een site aan het maken voor iemand die bezems verkoopt en die willen een bezem in de banner? Ja ok, dat mag. Wees je er wel van bewust dat marketing technisch gezien capibara's veel aantrekkelijker zijn. En ze hebben ook wel een beetje een vacht die op een bezem lijkt dus... Ik zeg niet dat het MOET, maar...

![image](https://user-images.githubusercontent.com/78969608/157194768-36943408-6a18-42c6-80db-6c9095486d89.png)

EN dan het grote moment! Het zogenaamde moment supreme. PUBLICEER je pagina en geniet van al je harde werk! Niets te zien? Waarom niet? We hebben een veld aangemaakt. We hebben een plaatje geselecteerd voor onze pagina. Waarom laat 'ie nou geen plaatje zien? Nou lieve kijkbuiskinderen dat komt omdat we wordpress nog moeten gaan vertellen dat we graag willen dat ons plaatje ergens weergegeven moet worden. En daar moeten we code voor gaan schrijven. Dus we gaan nu het diepe in!

![image](https://user-images.githubusercontent.com/78969608/157194988-d02f0e4b-a66b-4beb-8057-e94dbcd662fe.png)
Deze capibara gaat ook ACF velden maken. Dat kan je zien aan het feit dat ook hij het diepe in gaat. En aan die vertwijfelde blik in z'n ogen omdat dit de eerste keer is dat 'ie dat doet.

![image](https://user-images.githubusercontent.com/78969608/157195684-05a28d71-00bc-4d1e-8cc8-c7dd81f89354.png)


![image](https://user-images.githubusercontent.com/78969608/157195758-e675c612-a4f1-475b-a722-42724606ba89.png)

We moeten ons veld dus ergens gaan weergeven. En aangezien we een bannerafbeelding willen maken lijkt mij de handigste plek om dat te doen de header.php van ons thema. Mocht je nou geen header.php hebben kopieer er dan een van de parent theme of maak er zelf een aan. Hoe dat moet valt buiten de scope van deze tutorial. ik ga er even vanuit dat je een header.php in je thema hebt staan. 

![image](https://user-images.githubusercontent.com/78969608/157196040-5762aa40-9cc6-49b4-b0a6-1e3711113878.png)
Zo ziet mijn header.php er uit. Die van jou zal er misschien anders uitzien maar het idee is hetzelfde. We moeten een plek zoeken waar we een bannerafbeelding kunnen gaan weergeven. Dit is misschien even zoeken door je HTML om de juiste plek te vinden. Ik plaats hem onderaan in de header zodat het menu erbovenstaat en ik dan de afbeelding kan gaan weergeven. 



![image](https://user-images.githubusercontent.com/78969608/157200336-e1403540-a9bb-4c73-85f7-626fed969991.png)


![image](https://user-images.githubusercontent.com/78969608/157200433-cfdec423-2114-4d87-ace7-9dcd622c8264.png)
Weet je nog dat ik zei dat onze veld naam een van de belanghrijkste dingen van ons nieuwe veld was net? Niet? Heb ik echt gezegd, scroll maar naar boven. Die naam en de [get_field](https://www.advancedcustomfields.com/resources/get_field/) functie zijn waarschijnlijk de 2 belangrijkste dingen die je moet weten over ACF. Daarmee gaan we wordpress vertellen dat we dat specifieke veld willen hebben. Ik ga er ook even vanuit dat je een basiskennis PHP hebt en je deze lijn code snapt. We stoppen de informatie van onze get_field functie over onze afbeelding in een variabele. Die variabele gaan we zometeen gebruiken in onze img tag om het plaatje daadwerkelijk weer te geven.

![image](https://user-images.githubusercontent.com/78969608/157202705-ed4151bf-4c59-4248-9261-ed4ccf3f5e20.png)

Ok fijn. We hebben nu een variabele waar onze URL in staat, nu nog de HTML. We maken voor het gemak even een dov mete en class aan om onze img tag in te zetten en dan echo-en we vervolgens onze variabele. Als het allemaal nog wat onzeker voelt dan typ je deze code gewoon over. Maar ik neem aan dat je ongeveer snapt wat er zometeen gaat gebeuren. Onze variabele gaat zometeen de URL van het plaatje weergeven wat we op onze pagina hebben geselecteerd. Dit plaatje staat gewoon in de media library en die worden gewoon ergens opgeslagen en die URL gaan we zometeen zien. Goed dan, vergeet niet te saven. en dan gaan we nu kijken of we EINDELIJK iets op de pagina zien.

![image](https://user-images.githubusercontent.com/78969608/157201021-f882c7a7-3dbe-4815-b040-2ba7a3ab6635.png)

HIJ IS ER! ONS PLAATJE! JAJA! Lekker bezig. Voelt goed he? Ok, het moet nog een beetje gefatsoeneerd worden, maar we hebben ACF en wordpress zover gekregen om ons veld te laten zien en dat is toch al heel wat.

![image](https://user-images.githubusercontent.com/78969608/157201246-d884d7b7-121e-4916-810b-d0df1aaa882f.png)


![image](https://user-images.githubusercontent.com/78969608/157202108-e9e2da79-aac5-4f3c-ba02-54ca03d2f304.png)

In de editor van je browser kan je nu ook zien wat er gebeurd. Hij geeft dus de URL van het plaatje door wat we hebben geselecteerd op de pagina. Om het nog wat op te leuken drukken we er nog een regeltje of 2 CSS bij. 
![image](https://user-images.githubusercontent.com/78969608/157202250-e0b0ee1e-d95a-42d3-a3ae-13e33ec0f155.png)
En voila! Een echte bannerafbeelding die je zelf in het thema hebt gezet. Dat hele webdev gebeuren kan best leuk zijn hè? 

![image](https://user-images.githubusercontent.com/78969608/157203283-87ef5f48-4910-44e5-a306-722e385bf0e3.png)
Goed gedaan!

![image](https://user-images.githubusercontent.com/78969608/157296883-15687e7d-4968-41c0-b6b3-233be5c6a1da.png)
Nu mag je Joost of Patrick op telegram appen om te laten zien dat je coole shit gemaakt hebt. En die zullen je dan een schouderklopje geven. En namens mij ook een digitaal schouderklopje. Ik hoop dat je er wat aan hebt gehad.

## Doe het zelf idee
Je hebt nu dus die afbeelding maar wat als we nou text op die afbeelding willen hebben staan? Kan je zelf een veld maken waar je tekst in kan voeren en die op die afbeelding laten zien?

## FAQ
Daan ik heb je betrapt op het niet volledig formuleren van Nederlandse zinnen en er zitten ook spelvauten in je turtorial.






