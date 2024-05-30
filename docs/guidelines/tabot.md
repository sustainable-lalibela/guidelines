Describing a Manbara Tabot in ArcheoGRID
===

!!! warning "DRAFT version (2024-05-31)"
	
	This page documents a proposal of a Manbara Tabot description template we developed using Claire Bosc-Tiessé paper.
	
	**We'll have to harmonize this template with the one we've designed for the manuscripts.**
	
	DRAFT TO BE DISCUSSED!


The description of a manuscript contains these 5 sections:

1. Identification
- Physical description
- Intellectual content
- Origin and provenance
- Additional


## Identification


### Call number

> This call number is provided by the Sustainable Lalibela project. 'SL' stands for Sustainable Lalibela, 'ManbaraT' for Manbara Tābot, 'Lalibala' for the place name, followed by two or three capital letters representing the church, 'Museum' for the church museum, and then a sequential number assigned to an item in the respective church or museum collection.collection.

- mandatory
- `SL_ManbaraT_Lalibala_{AA}_{000}`


!!! example

	SL_ManbaraT_Lalibala_MD_001


### Other call numbers

> Other call numbers given outside of the Sustainable Lalibela project.

- **optional?**
- text

!!! example

	BMA 01, B.V.24, LMA 2, Mädhäné Alam 2, PA 054610, PA 054612, PA 054614.


### Current place of preservation

> Church or museum that has been guarding the object at the moment of description.

- mandatory
- enum

Values:

- Museum 
- Beta Madḫāne ʿĀlam 
- Beta Giyorgis 
- Beta Māryām 
- Beta Golgotā 
- Beta Masqal 
- Beta Gabrǝʾel 
- Beta ʾAmānuʾel 
- Beta Mārqorewos 
- Beta Libānos 
- Beta Danāgǝl


## Physical description

### Material

> Material refers to all visible types of materials used in creating the object's current appearance.

- mandatory
- enum

Values:

- Wood 
- Paints 
- Leather for covering legs 


### Technique

> Technique here refers to the method of distinguishing between carving the entire object from a single piece (monoxyle) and assembling several pieces into one object (assembled).

- mandatory
- enum

Values:

- monoxyle 
- assembled 


### Shape of the object

> The shape of the object refers to distinguishing between its square and cruciform shape.

- mandatory
- enum

Values:

- Square 
- Cruciform 


### Number of openings

> The term 'opening(s)' refers to one or two openings located on one or two sides of the object, leading to its inner part.

- mandatory
- enum

Values:

- On the upper side 
- On the south side 
- On the east side 
- On the north side 
- On the west side 
- On the undefined side 


### Carving technique

> The carving technique here refers to distinguishing semi-flat relief carving from other methods.

- mandatory
- enum

Values:

- Semi-flat relief carving 
- Other 


### Known dimensions

> If measured at all, the objects are measured as if they were square, regardless of their actual shape.

- mandatory
- boolean (Yes/No)


### Total height (in mm)

> **If known**. TBD

- optional
- integer (in mm)


### Width (in mm), if known 

> **If known**. TBD

- optional
- integer (in mm)


### Length (in mm), if known 

> **If known**. TBD

- optional
- integer (in mm)


### Height of the legs (in mm), if known 

> **If known**. TBD

- optional
- integer (in mm)


### Height of the box (in mm), if known 

> **If known**. TBD

- optional
- integer (in mm)



## Intellectual content


### Ornamental patterns

> If ornamental patterns are present, they are described here in generic groups such as 'cross', 'manbara tābot', 'arches', 'vegetal motifs', 'geometric motifs', or 'other' if none of the listed groups applies.

- mandatory
- enum / multiple choice

Values:

- Cross 
- Manbara tābot 
- Arches 
- Vegetal motifs 
- Geometric motifs 
- Others
- None


### Location of the ornamental patterns

> **If present**. If ornamental patterns are present, they are described above by generic groups such as 'cross', 'manbara tābot', 'arches', 'vegetal motifs', 'geometric motifs', or 'other' if none of the listed groups applies. This level of description includes the location where these ornamental patterns are observed. If there is only one opening, its side is considered to be oriented to the east, and the orientation of the other sides is defined accordingly. If there are two openings, sides’ orientation remains undefined.

- optional
- enum / multiple choice

Values:

- On the upper side 
- On the south side 
- On the east side 
- On the north side 
- On the west side 
- On the undefined side 
- On the legs 


### Figures

> Here 'figures' refer to human or human-like representations, with explicit naming of Jesus Christ and Mary, while saints or angels are grouped together. If identification is uncertain, the figure is classified as 'unknown'.

- mandatory
- enum / multiple choice

Values:

- Jesus Christ 
- Mary 
- Saint 
- Angel 
- Unknown 
- None 


### Location of figures

> **If present**. This level of description includes the location where the figure(s) are observed. If there is only one opening, its side is considered to be oriented to the east, and the orientation of the other sides is defined accordingly. If there are two openings, sides’ orientation remains undefined.

- optional
- enum

Values:

- On the upper side 
- On the south side 
- On the east side 
- On the north side 
- On the west side 
- On the undefined side 


### Location of the inscription

> **If present**. Inscription refers to carved characters. If present, they may be found on the box and/ or legs.

- optional
- enum

Values:

- Box 
- Legs 


### Transcription of the inscription

> **If present**. 

- optional
- text (amharic)

!!! example

	አነ፡ ላሊባላ፡ ንጉሥ፡ በስሞሙ፡ ለ፳፡ ወ ፬ ካህናተ፡ ሰማይ፡ ከመ፡ ይስአሉ፡ ኀበ፡ እግዚአብሔር[፡] [ከ]መ፡ ይስረይ፡ ኀጢአት26[፡] ወጌጋይየ[፡] አሜን[፡] ወአሜን[፡]


### Dedication

> TBD

- optional
- enum

Values:

- 24 heavenly priests 
- Cherubims 
- Mary 
- Paraclete 
- Hananiah, Azariah and Mishael 
- Saturday of Christians 
- Melchizedek 
- Four animals of the Apocalypse 
- Archangel Gabriel 
- Trinity 
- Cyriacus 
- George 
- Michael 
- Other 



## Origin and provenance


### Provenance

> Church(es) where the object was kept before it was placed in its current location for preservation.

- optional
- enum

Values:

- Beta Danāgǝl 
- Beta Madḫāne ʿĀlam 
- Beta Giyorgis 
- Beta Māryām 
- Beta Golgotā 
- Beta Masqal 
- Beta Gabrǝʾel 
- Beta ʾAmānuʾel 
- Beta Mārqorewos 
- Beta Libānos 


## Additional

### Conservation status

> The conservation status is described here using four categories: intact, partially burnt, partially broken, and repaired. A single object can have up to three categories applicable to it (e.g., partially burnt, partially broken, and repaired).

- mandatory
- enum

Values:

- Intact 
- Partially burnt 
- Partially broken 
- Repaired 
- Partially damaged 


### Affected part

> **If damaged**. The conservation status is described above using four categories: intact, partially burnt, partially broken, and repaired. A single object can have up to three categories applicable to it (e.g., partially burnt, partially broken, and repaired). This level of description includes the location where the damage(s) are observed. If there is only one opening, its side is considered to be oriented to the east, and the orientation of the other sides is defined accordingly. If there are two openings, sides’ orientation remains undefined.

- optional
- enum

Values:

- The upper side 
- The south side 
- The east side 
- The north side 
- The west side 
- Door(s) 
- Leg(s) 
- Upper corner(s) 
- Side corner(s) 
- Undefined 

### EMML/HMML Reproductions

> Microfilming or digitazation projects that took place before the Sustainable Lalibela project initiative.

- optional
- text


!!! example
	
	TODO


### Notes

> TBD

- optional
- text

!!! example

	TODO


### Bibliography

> TBD

- optional
- text (no formatting)

!!! example

	Bosc-Tiessé, C. 2010. ‘Catalogue des autels et meubles d’autel en bois (tābot et manbara tābot) des églises de Lālibalā: Jalons pour une histoire des objets et des motifs’, Annales d’Éthiopie, 25 (2010), 60-61.

