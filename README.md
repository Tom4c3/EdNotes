# Unity Editor Notes

A simple tool to add notes to GameObject in the Hierarchy or Objects in the Project panel. The notes data in the scene are kept in a hidden object tagged as `EditorOnly` so the data will not end up in your final builds. The data concerning project objects are kept in an asset next to the this tool's scripts by default.

Open the Note panel via menu: `Window > Notes`. Enter some text and press [Save].

Click on the gear icon to show the Editor Notes settings where you can change the icon to use to indicate that an object has a note attached.

- Label Expand: if you choose a Label icon then this determine if the colour expands full width or only object name length.
- Icon Position: select where icon should be shown if using icon type indicator.
	+ Left/Right edge of panel
	+ To Left/Right of the object's name
- Icon Offset: can be used to move the icon from the selected position

![screenshot](https://user-images.githubusercontent.com/837362/30640573-bb962954-9e03-11e7-88e9-1d03f2379195.png)


# How to install

 - Download this file
 - Drag & drop `EdNotes > Assets > EdNotes` on Unity project
 
October 24, 2022, I have confirmed that it works with Unity 2019.4.22f1.


