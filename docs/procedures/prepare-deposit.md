Preparing deposit folder
===


!!! note

    Sustainable Lalibela Project
    
    - Group 1. Desale, Tegegne, Alemu T., Abebe
	- Speaker: Desale


I have made my pictures and I'm back in the Lalibela Church Museum to prepare the deposit folder.

I need:

1. to transfer the pictures on the computer HD
2. to prepare the ArcheoGRID deposit folder


## 1. Transfering files


**2 Steps**

**\1. I open my personal folder inside the `Document` folder on the computer I use.**

- Click on the folder icon in the task bar (bottom of the screen).
- Open my personnal folder, eg `Documents/Fiseha`

**\2. I transfer the images from the memory card of the camera**

- Using a good working adaptor, I plug the memory card in the computer USB slot
- I open the directory with the Explorer
- **I select the relevant images**
- I copy/paste those selected images in my personal folder

I can organize my personal folder as I want. For instance I can create a folder for each type of object.


!!! example
	
	```
	Documents/
	fiseha/
		manuscripts/
			one_folder_per_manuscript/
		icons/
			one_folder_per_icon/
	mikiyas/
		gospels/
		mydocs/
	```



## 2. Prepare the archeoGRID deposit

**2 Steps**

**\1. Rename manually the object folder**

= the folder containing all the files of the object, eg all the images of a manuscripts)

I MUST always refer to that documentation to rename the folder (follow the namming rules).


**\2. Rename automatically the files inside the folder using Bulk Rename Utility**

Use the parent folder prefix option.

TODO: tutorial video



## File namming rules

### Namming objects

What will be the name of the object in ArcheoGRID?

For instance, what will be the name of:

- a manuscript?
- a manbara tabot?
- a cross?
- ?

Principle: the name of the object MUST be it's call number.

Important :

- No special characters
- No space

Structure of the call number of an object/name of the folder:

SL_MS_StLalibela_BMA_000


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


|Object type|2 letters code|
|-----------|--------------|
|Manuscript|MS|
|Manbara Tabot|MT|
|Cross|CR|
|Icons|IC|
|Paintings|PA|
|?|?|


!!! example
	
	35th manusucript stored in Lalibela Church Museum:  
	`SL_MS_StLalibela_LCM_035`

	4th cross stored in Beta Māryām Church:  
	`SL_CR_StLalibela_BMM_004`
	
	2nd Manbara Tabot of Beta Golgotā:  
	`SL_MT_StLalibela_BGA_002`


### Namming resources related to an object

Definition. A resource is a file of the objet: for instance an image of a manuscript, a text of an archive, an audio file of a gospel. Often, we have several resources for one object, for instance, all the images of a manuscript.

Principle. The prefix of the file MUST be the name of the parent folder (the name of the object), followed by the numbering.


Pattern: {object_name}_{numbering}.{extension}


Exemple

128th image of the 35th manusucript stored in Lalibela Church Museum

`SL_MS_StLalibela_LCM_035_0128.tif`


3rd image of the 2nd Manbara Tabot of Beta Golgotā

`SL_MT_StLalibela_BGA_002_0003.jpg`


