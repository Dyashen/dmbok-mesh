
Het boek is geschreven door Zhamak Deghani. Haar achtergrond is vrij IT-gericht. Zo heeft ze voor meerdere grote corporaties gewerkt binnen software architecture. 

In 2018 formuleerde Zhamak een eerste observatie van vaak voorkomende falingspatronen binnen data analyse bij grote organisaties. Ze observeerde waar organisaties exact mee worstelen. Zo stelde ze de eeuwenlange assumpties rond hoe we waarde uit data kunnen halen in vraag.

Dit boek is een verzameling van Zhamak en haar collega's hun kennis over data meshes. Zo komen er verschillende pragmatische problemen aan bod in het boek. Verder haalde Zhamak ook inspiratie uit '[How to move beyond a monolithic data lake to a distributed data mesh](https://martinfowler.com/articles/data-monolith-to-mesh.html).' van Martin Fowler.

Zo omvat het boek vijf hoofdstukken:
1. Wat is een data mesh waarin elk van de principes wordt omschreven.
2. Waarom een data mesh gebruiken en hier kan de lezer al inzien of de organisatie afgestemd is of juist niet.
3. Hoe kunnen technologisten en leidinggevenden een data mesh architecture ontwerpen en evalueren.
4. Hoe worden dataproducten, een van de concepten in een data mesh, worden ontworpen zonder compromissen.
5. Tot slot staat de schrijfster stil bij de ultieme aanzet om dergelijke projecten op start te brengen.
### Waarom het boek?
* Data management bij **analytische doeleinden** is altijd een probleem gebleken bij grote bedrijven.
	* Applicaties koppelen aan een gedeelde [[Data store]] was een ramp en omvatte ad-hoc coupling. Kernideeën, zoals het begrip 'klant' bij een commercieel bedrijf, worden binnen grote organisaties met andere datamodellen ontworpen.
	* Als antwoord hierop gingen enterprises hun [[Data decentraliseren|data centraliseren]]. Toch bleven data analytics gecentraliseerd, want datawarehouses zijn opgebouwd om een enterprise zo een opslagplaats van gecureerde en kritieke informatie op te slaan. De gecentraliseerde groep slaagt er echter niet in omdat ze geen goed begrip hebben op de data of de noden van de betrokken partijen, ofwel de mensen die de data 'consumeren'. De oplossing hierop is een [[Data lake|data lake]].

* Verder gaf Zhamak een conferentie 'Beyond the lake' tijdens een O'Reilly conference. 
	* Daar konden andere **data analisten en data scientists** relativeren met de huidige problematiek rond tijdelijke toegang tot kwaliteitsvolle en vertrouwbare data. 
	* **Data engineers** zijn de 'middle-man' en moeten zo rekening houden met niet-betrouwbare databronnen, ofwel upstream data, maar ook hoe ze data konden vormgeven zodat downstream dataproducten effectief gebruik konden maken zonder inmenging van de business.
	* **Leidinggevenden** zagen geen ROI in hun data en analytics oplossingen.

We zitten op een traject waarbij we wegstappen van gecentraliseerde data. Het eigenaarschap en de datamodellen verhuizen naar gedecentraliseerde modellen. Dat stelt organisaties in staat om waarde uit data op schaal te halen, ondanks een warrige organisatorische complexiteit.
* Zhamak wil zo een boek schrijven om voornamelijk de doelen van data mesh aan te halen en een algemene fundering geven voor verdere evoluties van data mesh implementaties.

### Doelgroepen voor dit boek

Het boek is gericht op een breed publiek. Daarnaast benadrukt de schrijfster ook om vertekeningen of vooroordelen los te laten en dit boek met een nieuwe mindset door te nemen.

* Analytical data users zoals data analisten of data scientists. Zo weten zij waar data mesh toe in staat is en hoe zij als actieve gebruiker ervan deel uit maken.
* Data providers zoals data engineers. Dit boek geeft een invulling hoe zij horen tussenin een operationeel en een analytisch systeem.
* Infrastructure product owners en data architects kunnen dit boek gebruiken als houvast bij het ontwerpen van nieuwe dataplatform. Zo kunnen zij van bij het ontwerpproces rekening houden met services die gedecentraliseerde data structuur en cross-functionele domeinteams ondersteunen.
* Data governance teams zodat ook zij mee zijn met de nieuwe structuur. Hun aanpak om governance doeen te kunnen behalen. Belangrijk is dat het boek ook nieuwe rollen introduceert rond data governance aanpakken.
* Data managers en executives kunnen ook dit boek doornemen om een grip te hebben op de huidige paradigm shift en hoe zij een data strategie kunnen formuleren.