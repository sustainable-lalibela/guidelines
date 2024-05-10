Recording manuscripts in the database
===


**https://www-dev.archeogrid.fr/edit,pft3d,manuscript_general,object,9098,11565**

****

- ArcheoGRID [`manuscript_general`](https://www-dev.archeogrid.fr/admin/editMetadataModel/pft3d/38) model
- ArcheoGRID [`Manuscrits`](https://www-dev.archeogrid.fr/project/5128?folder=10590) folder


## Elements

### Identification

#### `TITLE`

- definition: a generic title / label that can give a hint about the main content of the book. It is a title that is used by the community members to refer to the book orally or in the inventory lists. Here you have many options of such titles, choose the right one(s). Note that if the title you are looking for does not figure in the list, choose the variant “unidentified”.
- ?

!!! note

	Geez title (written in Latin alphabet) / its English translation / ref. Clavis BM (CAe)
	

#### `CALL NUMBER`

- definition: 
- mandatory?
- rule ?
- ?


!!! example

    SL_MS_Lalibala_MD_001 


#### `OTHER CALL NUMBERS`

- definition: 
- optional?
- ?

!!! example

	B10.IV.1, AM-LL-IV-16, LAL-IV-2002.5, ET-AM-LL-011-IV-001


#### `PROVENANCE`

- definition: place of preservation of the book. Choose the name of the church in the thesaurus.
- `Enum` type
- ?

!!! note

	If the church you are looking for does not figure in the list, contact the curator of the project to create one. 



#### `VERIFIED CURRENT LOCATION`

- definition: 
- thesaurus?
- ?


!!! warning

	Préciser la différence entre `PROVENANCE` et `VERIFIED CURRENT LOCATION`


### Physical description


#### `MATERIAL`

- definition: the material used for writing on it. Here you have only two options, parchment or paper, choose one.
- `Enum`: parchment | paper


#### `FOLIOS`

- definition: 
- ?


#### `HEIGTH`

- definition: 
- in mm

!!! note

	The height was measured before the digitization, it is on the metadata sheet, just copy it! 


#### `WIDTH`

- definition: 
- in mm

!!! note

	The width was measured before the digitization, it is on the metadata sheet, just copy it! 


#### `DEPTH`

- definition: 
- ?


#### `BINDING`

- definition: 
- ?

!!! example "Binding notice example"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! question

	-	Plats de bois
	-	Plats de bois couvert de cuir / estompé / autres décorations métalliques
	-	Tissus dans la couverture
	-	Dos



#### `SCRIBE`

- definition: Under ‘scribe(s)’ we understand a person who is explicitly named in the text as a scribe. Sometimes you have more than one scribe mentioned, sometimes you do not have any. 
- ?

!!! example "Scribe notice example"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! note

	Please leave this window empty.


### Origin and provenance

#### `DATE`

- definition: of what?
- format: `jj/mm/aaaa`
- ?


#### `COMISSIONER - PATRON`

- definition: a person who is named in the text and can be interpreted as a commissioner. Sometimes the text mentions a commissioner with his / her entire family, sometimes it does not mention anyone.
- ?

!!! note

	Please leave this window empty.


### Intellectual content


#### `CONTENT`

- definition: a description of all meaningful elements inside the book. Unless you have a pre-prepared description of the content, leave this window empty.
- ?

!!! example "Content notice example"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


#### `DECORATION`

- definition: any decorative element inside the book. Here you have only two options, if there are decorative elements, you answer ‘yes’, if there are no such elements, you answer ‘no’. 
- `boolean` (oui/non) 
- ?

!!! note

	Sous-catégories: harag / drawings / paintings (leur donner deux exemples à chaque fois). Yes or no pour chacun des trois.


### Additional

#### `CONSERVATION STATUS`

- definition: 
- values: good / medium / bad

!!! note

	Depending of the state of the book, you have three choices to evaluate it. If nothing is damaged, conservation status is good. If the binding is damaged, conservation status is bad. If the binding is not damaged, but there are other problems, and you think the book can be still used for reading without any risk, then choose ‘medium’.



#### `Notes d'archives`

- definition: 
- `boolean` (oui/non) 
- ?


#### `REPRODUCTIONS`

- definition: 
- ?


### Not in the model… Keep?

#### `CURRENT LOCATION AT THE MOMENT OF THE DIGITALIZATION`

If the manuscript is still kept in the church where it comes from, repeat the name of the church.

The manuscripts are transferred to the museum for digitalization, but do not consider that in this case museum is their current location at the moment of the digitalization. Choose “museum” location only if the book is permanently kept here.
For example, the provenance could be “Beta Māryām”, the current localization could be “Beta Māryām” or “Museum”.


#### PERIOD OF PRODUCTION BASED ON WRITING

pre-1350; 1350-1450; 1450-1550; 1550-1650; 1650-1750; 1650-1850; 1850-1900; 2000-

Under ‘period of production’ we understand a period to which the writing can be dated based on palaeographical analysis. 

Please leave this window empty.


#### DATATION

Under ‘datation’ we understand a reference to a specific date or mention of a historical figure which inform the date of the production of the book.

- Yes /no
- commissionner
- chronologie absolue (calendrier grégorien)

Please leave this window empty.


#### COLOPHON

Under a ‘colophon’ we understand a note giving some information about the production.

-	YES / NO
-	Texte

Please leave this window empty.


#### ADDITIONAL NOTES

Under ‘archival notes’ we understand all notes that are different from the main content and as such, additional to the main content. Here you have only two options, if there are such additional notes, you answer ‘yes’, if there are no such notes, you answer ‘no’. In case of doubt, please contact the curator of the project

Please leave this window empty.

-	Text: geez and traduction


#### NUMBER of FOLIOS

The number of folios was calculated before the digitization, it is on the metadata sheet, just copy it!


#### THICKNESS

(in mm)

The thickness was measured before the digitization, it is on the metadata sheet, just copy it! 


#### WEIGHT 

The weight was measured before the digitization, it is on the metadata sheet, just copy it! 


#### NOTES

Here you have an option to note something important about the book, particularly you can shortly specify something what you could not specify concerning the decoration / additional notes or conservation status. Something that might serve as a sign for further users. Note that you do not need to write anything that comes from a ‘general knowledge’, something that is not strictly related to this particular manuscript. If you have nothing to add, leave this window empty. 

#### Bibliography 

To be discussed


## Appendix

- [TEI Manuscript Description module documentation](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html)
- [Beta maṣāḥǝft TEI Guidelines](https://betamasaheft.eu/Guidelines/)
- [BnF Manual for cataloguing medieval manuscripts](https://kitcat.bnf.fr/consignes-catalogage/manuel-de-catalogage-des-manuscrits-medievaux)
