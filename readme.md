## Dropzone.js Multiupload with rename functionality




### Scenrio: User wants to upload logos of tv channels/sports team etc, if he uploads one by one it is a hassle. 

- Rough design, how UI might look(How I intially imagined it to be)


![UI drawn using excalidraw](https://raw.githubusercontent.com/sahilkashyap64/dropzone-sortablejs-multiupload-rename/master/img/UI%20formultiupload%20and%20rename.png)


## Used these js lib
 
| Lib | Version | Use |
| ------ | ------ | --- |
| dropzone.min.js | ^5.9.3 | Multi drop images |
| Sortable.js | ^* | Sort dropzone instances|
| select2.min.js | ^4.0.13 | For multiselect|
| jquery.js | ^0.3.1 | simple add/remove items from dom|

Using Html drag and drop API, was able to create the ui.
Renaming is done via server side,I just pass 2 arrays
- Files
- Names

Simply merge the arrays,save the file.

https://user-images.githubusercontent.com/32007662/147849196-5ba3c92c-1fd4-49e4-a83f-e7e998ba05bb.mp4


