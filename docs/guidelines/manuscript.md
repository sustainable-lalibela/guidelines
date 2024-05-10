Recording manuscripts in the database
===


- ArcheoGRID model #38, [`manuscript_general`](https://www-dev.archeogrid.fr/admin/editMetadataModel/pft3d/38) – *Modèle d’enregistrement d’un manuscrit*
- ArcheoGRID [`Manuscrits`](https://www-dev.archeogrid.fr/project/5128?folder=10590) folder


## Elements

### Identification


#### Call number

> This call number is given by the Sustainable Lalibela project. SL stands for Sustainable Lalibela, MS for manuscript, Lalibala for a place name, two capital letters for the church, then a sequential number of a manuscript item in the respected church collection.

- mandatory
- `SL_MS_Lalibala_{AA}_{000}`


!!! example

    SL_MS_Lalibala_MD_001 
    

#### Other call numbers

> Other call numbers given outside of the Sustainable Lalibela project.

- optional?
- text


!!! example

	B10.IV.1, AM-LL-IV-16, LAL-IV-2002.5, ET-AM-LL-011-IV-001
	

#### Title

> Here ‘title’ stands for a generic title / label that can give a hint about the main content of the book. It is a title that is used by the community members to refer to the book orally or in the inventory lists. They are registered according to the following schema: Geez title (written in Latin alphabet) / its English translation. If Clavis BM id (CAe) is available, it is provided as well.

- mandatory
- enum

Values:

- Bāḥra ḥassāb / Computus (CAe 1195) 
- Baralām wa-Yǝwāsǝf / Book of Barlaam and Josaphat (CAe 1199) 
- Baruch 
- Bəluy Kidān / Old Testament (CAe 3530) 
- Dāwit / Psalter (CAe 2701) 
- Dǝggʷā / Antiphonary (CAe 3178) 
- Dǝrsān za- Yoḥannǝs ʾafa warq / Homily of John Chrysostom 
- Dǝrsāna Gabrǝʾel / Homily on the Archangel Gabriel (CAe 5901) 
- Dǝrsāna Mikāʾel / Homily of Michael (CAe 5898) 
- Dǝrsāna za-Yāʿqob ʿza-hagara Sǝrug / Homily of James of Sarug 
- Dǝrsāna ʿUrāʾel / Homily of (Archangel) Uriel (CAe 1302) 
- Dǝrsānāt / Homiliary (CAe 5856) 
- Dǝrsānāt / Homiliary (CAe 5856) and Gadla samāʿtāt / Acts of martyrs (CAe 1493) 
- Fǝtḥa nagaśt / The Law of the Kings (CAe 1395) 
- Gadla Fāsiladas / Life of Basilides (CAe 1893) 
- Gadla Gabra Manfas Qǝddus / Life of Gabra Manfas Qǝddus (CAe 1451) 
- Gadla Giyorgis (Lydda) / Life of Giyorgis (Lydda) (CAe 1455) 
- Gadla Hanna and Joachim / Life of Anna and Joachim 
- Gadla ḥawāryāt / Contendings of the Apostles (CAe 1461) 
- Gadla Lālibalā / Life of Lālibalā (CAe 4970) 
- Gadla Lālibalā / Life of Lālibalā (CAe 4970), Gadla Yǝmrǝḥanna Krǝstos / Life of Yǝmrǝḥanna Krǝstos (CAe 1516) 
- Gadla Lālibalā / Life of Lālibalā (CAe 4970), Gadla Masqal Kǝbrā / Life of Masqal Kǝbrā (CAe 1481) 
- Gadla Libānos / Life of Libānos (CAe 1473) 
- Gadla Naʾakkʷǝto Laʾab / Life of Naʾakkʷǝto Laʾab (CAe 1484) 
- Gadla samāʿtāt / Acts of martyrs (CAe 1493) 
- Gadla Takla Hāymānot / Life of Takla Hāymānot (CAe 3973) 
- Gadla Yǝmrǝḥanna Krǝstos / Life of Yǝmrǝḥanna Krǝstos (CAe 1516), Gadla Lālibalā / Life of Lālibalā (CAe 4970), Gadla Naʾakkʷǝto Laʾab / Life of Naʾakkʷǝto Laʾab (CAe 1484) 
- Gadla ʾAbrǝhām / Testament of Abraham (CAe 4058 ) 
- Gǝbra ḥawāryāt / Acts of the Apostles (CAe 1019) 
- Gǝbra Ḥǝmāmāt / Lectionary of the Holy Week (CAe 1544) 
- Hāymānota ʾabaw / The Faith of the Fathers (CAe 1586) 
- Malāʾǝkt / Epistles (CAe 1352) 
- Malkǝʾa Giyorgis / Malkǝʾ-hymn to St George (CAe 3100) 
- Malkǝʾa gubāʾe / The Collection of Images (CAe 1850) 
- Maqābis / Book of Maccabees (CAe 1819) 
- Maṣḥafa gǝnzat / Book of the Funeral Ritual (CAe 1931) 
- Maṣḥafa gǝṣṣāwe / Lectionary (CAe 1932) 
- Maṣḥafa ḥǝywat / Treatise of the life (CAe 4945) 
- Maṣḥafa manakosāt / Book of monks (CAe 1946) 
- Maṣḥafa saʿātāt / Book of the Hours (CAe 3575) 
- Maṣḥafa ṭǝmqat / Book of the Baptism (CAe 1975) and Maṣḥafa gǝnzat / Book of the Funeral Ritual (CAe 1931) 
- Maṣḥafa ʿarke / Book of ʿarke-hymns 
- Mawāśǝʾǝt 
- Mazmura fǝśśuḥān / Psalter of the Jubilant (CAe 2001) 
- Mǝʿrāf / Common of the Office (CAe 3186) 
- Nagara Māryām / Story of Mary (CAe 2051) 
- Nagaśtāt / Books of Kings (CAe 1719) 
- Qerǝllos / Cyril I (CAe 3309) 
- Qǝddāse / Book of the Consecration (CAe 1960) 
- Ṣalot wa-ʾastabqʷǝʿot / Prayer of supplication (CAe 3582) 
- Saʿātāt za-lelit / Hours of the night 
- Sǝnkǝssār / Synaxarion (CAe 2375) 
- Sǝnkǝssār / Synaxarion: first half of the year (CAe 2375) 
- Sǝnkǝssār / Synaxarion: second half of the year (CAe 2375) 
- Sinodos 
- Taʾammǝra Lālibalā / Miracles of Lālibalā (Cae 6913), Taʾammǝra Māryām / Miracles of Mary (CAe 3584/3585) 
- Taʾammǝra Māryām / Miracles of Mary (CAe 3584) 
- Taʾammǝra Māryām / Miracles of Mary (CAe 3584), Taʾammǝra ʾIyasus / Miracles of Jesus (CAe 2382) 
- Taʾammǝra ʾIyasus / Miracles of Jesus (CAe 2382) 
- Tǝrgʷāme Dāwit / Commentary of the Psalter (CAe 3182) 
- Ṭəlləq ya-bərānnā sǝʿəl 
- Ṭobyā / Tobit (CAe 2473) 
- Wangel za-Mārqos / Gospels of Mark (CAe 1882) and Wangel za-Mātewos / Gospel of Mathew ( CAe 1558) 
- Wangel za-Mātewos / Gospel of Mathew (CAe 1558) 
- Wǝddāse ʾAmlāk / Praise of God (CAe 2505) 
- ʾAmmǝstu ʾaʿǝmāda mǝśṭir / The Five Pillars of Mystery (CAe 1097) 
- ʾAnkariṭos / Ancoratus (CAe 1107) 
- ʾAnqaṣa nǝssǝḥa / The Gate of Penance (CAe 1111) 
- ʾAragāwi manfasāwi / The Spiritual Elder (CAe 3989) 
- ʾArbāʿtu wangel / Four Gospels (CAe 1560) 
- unidentified 
- Wǝddāse Māryām / Praise of Mary (CAe 5639) 
- Psalms 
- Prayers 



### Physical description


#### Writing support

> Writing support stands for the material used for writing on it.

- mandatory
- enum

Values:

- parchment 
- paper 



#### Number of folios

> The number of folios reflects a number of folios, without making any difference for protective leaves.

- mandatory
- integer


#### Height

> Outer height of the manuscript, i.e. height of cover, if present.  

- mandatory
- integer (in mm)

#### Width

> Outer width of the manuscript, i.e. width of cover, if present.  

- mandatory
- integer (in mm)


#### Thickness

> Thickness of the manuscript, including the boards, if present.  

- mandatory
- integer (in mm)


#### Weight

> The wight of the manuscript.  

- optional
- integer (in g)



#### Bookbinding description

> General description of the bookbinding that does not require any special codicological competence.

- mandatory
- enum

Values:

- Detached folios 
- Bare binding 
- Bare wooden boards 
- Wooden boards covered with leather 
- Wooden boards covered with leather and textile 
- Wooden boards covered with metal 



### Origin and provenance

#### Provenance

> Here ‘provenance’ stands for a church where the book was kept before it entered the Lalibala church museum and became part of museum’s permanent collection.

- optional
- enum

Values:

- Beta Danāgǝl 
- Beta Gabrǝʾel 
- Beta Giyorgis 
- Beta Golgotā 
- Beta Libānos 
- Beta Madḫāne ʿĀlam 
- Beta Mārqorewos 
- Beta Māryām 
- Beta Masqal 
- Beta ʾAmānuʾel 
- Beta ʿUraʾel 


!!! note

	If the church you are looking for does not figure in the list, contact the curator of the project to create one. 



### Intellectual content


#### Decoration

> Here ‘decoration’ stands for any decorative element inside the book that falls into one of the four categories ( harag / drawing / painting / none).

- mandatory
- enum

Values:

- ḥarag 
- drawing 
- painting 
- none 


### Additional

#### Conservation status

> Here ‘conservation status’ stands for a general state of the book. If nothing is damaged, conservation status is good. If the binding is damaged, conservation status is bad. If the binding is not damaged, but there are other problems, although the book can be still used for reading without any risk, its conservation status is ‘medium’.

- mandatory
- enum

Values:

- good 
- medium 
- bad 


#### EMML/HMML Reproductions

> Microfilming or digitazation projects that took place before the Sustainable Lalibela project initiative.

- optional
- text


!!! example
	
	TODO

#### Notes

> ???

- optional
- text



## Previous Model, for discussion

### Identification > `TITLE`

> A generic title / label that can give a hint about the main content of the book. It is a title that is used by the community members to refer to the book orally or in the inventory lists. Here you have many options of such titles, choose the right one(s). Note that if the title you are looking for does not figure in the list, choose the variant “unidentified”.


!!! note

	Geez title (written in Latin alphabet) / its English translation / ref. Clavis BM (CAe)

!!! warning

	We don't have that information anymore. Different definition than actual `title` (historical information). Identification / Intellectual content


### Identification > `PROVENANCE`

> Place of preservation of the book. Choose the name of the church in the thesaurus.

!!! warning

	We don't have that information anymore. Different definition than actual `provenace` (historical information)


### Identification > `VERIFIED CURRENT LOCATION`

> ?

!!! warning

	Préciser la différence entre `PROVENANCE` et `VERIFIED CURRENT LOCATION`



### PhysDesc > `SCRIBE`

> Under ‘scribe(s)’ we understand a person who is explicitly named in the text as a scribe. Sometimes you have more than one scribe mentioned, sometimes you do not have any. 


!!! example "Scribe notice example"

    TODO


### Origin > `DATE`

> of what?

!!! warning

	No mention of (creation) date in the actual model


### Origin > `COMISSIONER - PATRON`

> A person who is named in the text and can be interpreted as a commissioner. Sometimes the text mentions a commissioner with his / her entire family, sometimes it does not mention anyone.



### Content > `CONTENT`

> A description of all meaningful elements inside the book. Unless you have a pre-prepared description of the content, leave this window empty.
- ?

!!! warning

    No description of the intellectual content in the actual model



### Additional > `Notes d'archives`

> ?


## Old ideas to discuss


### PERIOD OF PRODUCTION BASED ON WRITING

> Under ‘period of production’ we understand a period to which the writing can be dated based on palaeographical analysis. 

pre-1350; 1350-1450; 1450-1550; 1550-1650; 1650-1750; 1650-1850; 1850-1900; 2000-


### DATATION

> Under ‘datation’ we understand a reference to a specific date or mention of a historical figure which inform the date of the production of the book.

- Yes /no
- commissionner
- chronologie absolue (calendrier grégorien)


### COLOPHON

> Under a ‘colophon’ we understand a note giving some information about the production.

-	YES / NO
-	Texte

Please leave this window empty.


### ADDITIONAL NOTES

> Under ‘archival notes’ we understand all notes that are different from the main content and as such, additional to the main content. Here you have only two options, if there are such additional notes, you answer ‘yes’, if there are no such notes, you answer ‘no’. In case of doubt, please contact the curator of the project


### NOTES

> Here you have an option to note something important about the book, particularly you can shortly specify something what you could not specify concerning the decoration / additional notes or conservation status. Something that might serve as a sign for further users. Note that you do not need to write anything that comes from a ‘general knowledge’, something that is not strictly related to this particular manuscript. If you have nothing to add, leave this window empty. 

### Bibliography 

> To be discussed


## Appendix

- [TEI Manuscript Description module documentation](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html)
- [Beta maṣāḥǝft TEI Guidelines](https://betamasaheft.eu/Guidelines/)
- [BnF Manual for cataloguing medieval manuscripts](https://kitcat.bnf.fr/consignes-catalogage/manuel-de-catalogage-des-manuscrits-medievaux)
