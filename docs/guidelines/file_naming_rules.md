File naming rules
===


What will be the name of the object in ArcheoGRID?

For instance, what will be the name of:

- a manuscript?
- a manbara tabot?
- a cross?
- ?



!!! warning
	
	- No special characters
	- No space


## Naming pattern of an object


!!! tip "Principle"

	The name of the object MUST be its call number.
	
	`SL_{AA}_StLalibela_{BBB}_{000}`
	
	Where:
	
	- `{AA}` is the 2 letters code describing the type of the object.
	- `{BBB}` is the 3 letters code describing the **repository** institution.
	- `{000}` is the sequencial number of the object –**numbering starts at `001` for each repository.**




### Code lists

|Object type|2 letters code|
|-----------|--------------|
|Manuscript|MS|
|Manbara Tabot|MT|
|Cross|CR|
|Icons|IC|
|Paintings|PA|
|?|?|



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
	
	35th manusucript stored in Lalibela Church Museum:  
	`SL_MS_StLalibela_LCM_035`

	4th cross stored in Beta Māryām Church:  
	`SL_CR_StLalibela_BMM_004`
	
	2nd Manbara Tabot of Beta Golgotā:  
	`SL_MT_StLalibela_BGA_002`


## Naming pattern of a resource related to an object


**Definition**. A resource is a file of the objet: for instance an image of a manuscript, a text of an archive, an audio file of a gospel. Often, we have several resources for one object, for instance, all the images of a manuscript.


!!! tip "Principle"

	The resource name must be prefixed by the name of the object to which it is linked.
	
	`{object_name}_{000}.{extension}`
	
	Where:
	
	- `{object_name}` is the name of the object (e.g. `SL_MS_StLalibela_LCM_035`).
	- `{000}` is the numbering of the resource (e.g. `0146`).
	- `{extension}` is the file extension describing the format of the resource (e.g. `tif`).
	
	
!!! example	

	the 128th image of the 35th manusucript stored in Lalibela Church Museum  
	`SL_MS_StLalibela_LCM_035_0128.tif`
	
	the 3rd image of the 2nd Manbara Tabot of Beta Golgotā  
	`SL_MT_StLalibela_BGA_002_0003.jpg`
	

