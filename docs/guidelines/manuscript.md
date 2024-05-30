Recording manuscripts in the database
===


The description of a manuscript contains these 5 sections:

1. Identification
- Physical description
- Origin and provenance
- Intellectual content
- Additional



## Identification


### Call number

> The call number given by the Sustainable Lalibela project.

- required
- pattern: `SL_MS_StLalibela_{AAA}_{000}`

Call number parts:

- `SL`: Sustainable Lalibela
- `MS`: type of the object (here manuscript)
- `StLalibela`: name of the monastry (Saint Lalibela)
- `AAA`: 3 letters code of the repository institution (actual location of storage) – TBD
- `ddd`: 3 digits sequential number


|Repository institution|3 letters code|
|----------------------|--------------|
|Beta Danāgǝl|BDL|
|Beta Gabrǝʾel|BGL|
|Beta Giyorgis|BGS|
|Beta Golgotā|BGA|
|Beta Libānos|BLS|
|Beta Madḫāne ʿĀlam|BMA|
|Beta Mārqorewos|BMS|
|Beta Māryām|BMM|
|Beta Masqal|BML|
|Beta ʾAmānuʾel|BAL|
|Beta ʿUraʾel|BUL|
|Lalibela Church Museum|LCM|
|Lalibela Cultural Center|LCC|


!!! example

    SL_MS_StLalibela_BGO_018
    
    SL_MS_StLalibela_MUS_107
    


### Other call numbers

> Other (old or new) call numbers given outside of the Sustainable Lalibela project. In the case of an old one, never update it.
> 
> If the manuscript is already described in the 2022 inventory of Amhara regional Culture and Tourism Bureau, or in the Ethiopia national Inventory, you **MUST** give the call number/identification number of the manuscript in this inventory.
 

- optional
- text


!!! warning

	Create a new field for each different call number (click `+` button), and DON'T write several call numbers in the same field.


!!! note

	For former call numbers, you may need to add some contextual information, explaining where the old call number comes from –see example below.


!!! example
	
	AM-LL-IV-16
		
	ET-AM-LL-011-IV-001
	
	EMML-8878 (Ethiopian Microfilm Manuscript Library)
	

### Title of the manuscript

> Here ‘title’ stands for a generic title / label that can give a hint about the main content of the book. It is a title that is used by the community members to refer to the book orally or in the inventory lists. They are registered according to the following schema: Geez title (written in Latin alphabet) / its English translation. If Clavis BM id (CAe) is available, it is provided as well.

- required
- single value selection

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

**TODO: update the list of titles**


## Physical description


### Height

> Outer height of the manuscript, i.e. height of cover, if present.  

- required
- integer (in cm)


### Width

> Outer width of the manuscript, i.e. width of cover, if present.  

- required
- integer (in cm)


### Thickness

> Thickness of the manuscript, including the boards, if present.  

- required
- integer (in cm)


### Weight

> The weight of the manuscript.  

- optional
- integer (in g)


### Writing support

> Writing support stands for the material used for writing on it.

- required
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msph1sup](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msph1sup)
- single value choice

Values:

- parchment 
- paper 


### Folios numbering

> Continuous numbering of the leaves of the manuscript –without making any difference for protective, opening or closing leaves.
> 
> The number of folios reflects a number of folios, 

- required
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msph1ext](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msph1ext)
- integer

!!! Example

	TODO


### Collation

> A description of a book's current and original structure –the arrangement of its leaves and quires.

- optional
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msph1col](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msph1col)
- text

!!! Example

	4 quires: quires 1 and 2 contain 8 leaves. Quires 3 and 4 contain 6 leaves.


### Layout description

> A description of the layout of the manuscript, e.g. number of lines, of columns… ????

- optional
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msphla](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#msphla)
- text

!!! Example

	The script has 30 lines, 2 columns but the ruling and pricking are relatively not visible.


### Bookbinding description

> General description of the bookbinding that does not require any special codicological competence.

- required
- single value choice

Values:

- Detached folios
- Leather binding 
- Bare binding 
- Bare wooden boards 
- Wooden boards covered with leather 
- Wooden boards covered with leather and textile 
- Wooden boards covered with metal 


### Leather case

> Is the manuscript kept in a leather case? Tick if yes.

- optional
- boolean



## Origin and provenance

### Provenance

> Here ‘provenance’ stands for a Lalibela church where the manuscript was kept before it entered in its actual repository institution (e.g. a museum or a church).

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

	If the provenance place you are looking for does not figure in the list, contact the curator of the project to create one. 


### History

> A free description (using prose paragraphs) of the full history of the manuscript: e.g. history of the manuscript's transmission and acquisitions.

> Any information concerning the origin of the manuscript (or its parts), and concerning the process by which the manuscript entered the repository institution.

- optional
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#mshy](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html#mshy)
- text

!!! example
	
	TODO



## Intellectual content

### Languages

> Language identification of the content of the manuscript.

- required
- multiple values choices

Values ([ISO_639-2](https://en.wikipedia.org/wiki/List_of_ISO_639-2_codes)):

- `amh`: Amharic
- `ara`: Arabic
- `eng`: English
- `gez`: Geʽez
- `heb`: Hebrew


### Manuscript content

> A general description of the content of the manuscript – using informal prose paragraphs. 

- optional
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-msContents.html](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-msContents.html)
- text

!!! example
	
	TODO

### Manuscript item(s)

> Description of an individual work within the intellectual content of the manuscript.


- optional
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-msItem.html](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-msItem.html)
- text


!!! note

	You are supposed to be able to give a title or an author to each Manuscript item.
	

!!! warning

	Create a new item for each different work (click `+` button), and DON'T describe several works in the same `Manuscript item` field.


!!! example
	
	TODO



### Decoration

> Here ‘decoration’ stands for any decorative element inside the manuscript that falls into one of the four categories ( ḥarag / drawing / painting / none).

- required
- multiple values choice

Values:

- ḥarag
- drawing
- painting
- none –if no decoration


## Additional


### Conservation status

> Here ‘conservation status’ stands for a general state of the book. If nothing is damaged, conservation status is good. If the binding is damaged, conservation status is bad. If the binding is not damaged, but there are other problems, although the book can be still used for reading without any risk, its conservation status is ‘medium’.

- required
- single value choice

Values:

- good 
- medium 
- bad 


### EMML/HMML Reproductions

> Already existing digitization made during the EMML or the HMML projects
> 
> - EMML: Ethiopian Manuscript Microfilm Library
> - HMML: Hills Museum Manuscript Library

- optional
- text


!!! example
	
	Digitization available in HMML, under call number…


### Repository

> The institution where the manuscript is stored.

!!! note

    `Respository` is different from `Provenance`: the repository is the place where the manuscript is stored. For instance, the repository of a manuscript whose provenance is Beta Māryām can be Lalibela Church Museum.

- required
- see [https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-repository.html](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-repository.html)
- single value choice

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
- Lalibela Church Museum
- Lalibela Cultural Center


### Ownership

> The owner (institution) of the manuscript. TBD


### Comments

For free notes, it is possible to use ArcheoGRID comments: on the object card, click on `Comment` button.



## Appendix

- [TEI Manuscript Description module documentation](https://tei-c.org/release/doc/tei-p5-doc/en/html/MS.html)
- [Beta maṣāḥǝft TEI Guidelines](https://betamasaheft.eu/Guidelines/)
- [BnF Manual for cataloguing medieval manuscripts](https://kitcat.bnf.fr/consignes-catalogage/manuel-de-catalogage-des-manuscrits-medievaux)


TDB:

- Datation: under ‘datation’ we understand a reference to a specific date or mention of a historical figure which inform the date of the production of the book.
- Scribe(s): under ‘scribe(s)’ we understand a person who is explicitly named in the text as a scribe. Sometimes you have more than one scribe mentioned, sometimes you do not have any. 
- Comissioner _ Patron: A person who is named in the text and can be interpreted as a commissioner. Sometimes the text mentions a commissioner with his / her entire family, sometimes it does not mention anyone.
