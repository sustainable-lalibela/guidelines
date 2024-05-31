Tutorial. Making ArcheoGRID deposit
===


## 1. Copy data on Lalibela Server

Put resources on the main folder for resources that would be named : Resources

Example :
!!! example

	```
    /mnt/data/sustainablelalibela/LALIBELA_eglises_rupestres/Resources
    ```




Resources can be :

- Manuscripts
- Cross
- Manbara Tabot
- Vestiments 

So we have one folder for each type of resources : 

```
    /mnt/data/sustainablelalibela/LALIBELA_eglises_rupestres/Resources/Manuscripts
    /mnt/data/sustainablelalibela/LALIBELA_eglises_rupestres/Resources/Cross
    /mnt/data/sustainablelalibela/LALIBELA_eglises_rupestres/Resources/Manbara_tabot
    ...
```


In the Lalibela server, copy data on project folders, in the resources folder on the type of the resources concerned.


## 2. Synchronize data from dashboard admin in ArcheoGRID

- First, log in the ArcheoGRID system with the "scribe" profile
- Go to the dashboard
- Click on the Files menu  "Add / synchronize data"
- Select Branch "Collaborative 3D projects". This is allways this branch to select
- Select project "Lalibela_eglises_rupestres" and Validate

- if the data to synchronize are data of a manuscript, then synchronize the folder : LALIBELA_eglises_rupestres/Resources/Manuscripts
- if the data to synchronize are data of a Vestiments, then synchronize the folder : LALIBELA_eglises_rupestres/Resources/Vestiments


To synchronize the folder :

- select the name of the folder
- select "Folders and files" mode
- select "No" for delete
- select "yes" for recursion
- Validate

There is 2 parts for synchronizaion,
first part is the folder of the manuscript, for example "SL_MS_StLalibela_BGA_001"
then click on **Execute** to continue with the files

There is a message with information of data synchronized (how many files)


## 3. Grant permissions

- go to the dashboard
- Click on the Groups menu "Groups permissions"
- select a group with the name of the group
- select the branch : allways the same branch :"Collaborative 3D projects"
- submit the form


Select the new folder in the "forbidden folder's box" on the right panel
and clik on one of the "double arrow" to give permissions

- Top arrows (<<): read only permissions to have access and see the resources of the folder (upper left box)
- Bottom arrows (<<): read and write permissions to be able to see and add metadata on the resources of the folder (down left box)
