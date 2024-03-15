
In this zip file included both fyp1 and fyp2
------------------------------------------------------

FYP1____________
	- login.py is used to run the fyp1 programme
	- gui.py is used for test the face feature capture by modifying other people code.

##
 IF only want to know how to connect to the pc cam, can just only open the **gui.py** and look at lines 85 to 91 for connecting the pc cam, then lines 129 is for displaying in the window, which is pre-created "["-IMAGE-"]" in layout.
	### FOR "gui.py" just only have to install the cv2 packages
	
##


FYP2_____________________________________________________________________________
ALL CODE INSIDE Path "GUI"

libraries have to install to run the code:
 *normally will use command to install*
    # pip install 'package_name'

 *more easier way if use pycharm or intellij*
   *go the IDEA find setting > Project > Python Interpreter 
	click the + to add the needed libraries or packages*

## can also follow the link below to install the packages
https://www.geeksforgeeks.org/how-to-install-pip-on-windows/

___Libraries / Packages Installed___
  [
	1. Pillow
	2. PySide2
	3. dlib
	4. face-recognition
	5. face-recognition-models
	6. matplotlib
	7. numpy
	8. opencv-python
	9. pandas
	10. pyparsing
	11. wheel
    **i think all above is important, else can view the screenshot i added in zip to compare. if using IDEA, can just click "alt" + "enter" to check the error.**
]

im using python 3.9, in not sure others version is working or not, because last time im using python 3.8, i cant install the "wheel" library.

***
	Main.py is used to run the whole programme
	all the .py file named with "main" are needed to support the programme, named 		with "UI" are the UI display, then others are for testing not applied in main 		programme 
***

** Others .py can also operate independently except main_faceRecognition.py, this .py is use to recognize face features, encoding the image and get ready to match with the captured face.


***VERY IMPORTANT***
*************
IF want to share the programme with others, kindly remove the files "Occupants.db" and all the photo in file "images" and all the .csv files but dont remove the file if not the programme will not working.... else have to change the path_name in main_cam1.py and main_cam2.py at line 19 to 
sfr.load_encoding_images("new_path_name/")

#IF deleted the Occupants.db, i suggest run the main_occupants.py first to create the occupants record.
*************