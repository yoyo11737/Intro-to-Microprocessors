In the Express Web IDE right click on the project then "Package as MPLAB X Project"

![alt text](https://github.com/RShankar/Intro-to-Microprocessors/blob/master/MPLab%20X%20IDE/21.png "Package as MPLAB X Project")

This will download a .ZIP file which will contain a folder that ends with .X place this folder in your IDE projects folder. Then open the project in MPLAB X IDE. The 3rd icon is the open button navigate to where you unzipped the zip file to, Your IDE Projects folder.

![alt text](https://github.com/RShankar/Intro-to-Microprocessors/blob/master/MPLab%20X%20IDE/22.png "Open")

Now that you have the project in the IDE there is a small problem with the export/Import problem there is no compiler assigned to this project. __You will have to assign the compiler__ 

To start with right click on the project and go to properties 

![alt text](https://github.com/RShankar/Intro-to-Microprocessors/blob/master/MPLab%20X%20IDE/23.png "Property")

in the conf: Section you will see the complier toolchain section has nothing selected

![alt text](https://github.com/RShankar/Intro-to-Microprocessors/blob/master/MPLab%20X%20IDE/24.png "No comp")

Select the XC8 Compiler and click ok. Your project should now work exactly how it did in the Xpress IDE

![alt text](https://github.com/RShankar/Intro-to-Microprocessors/blob/master/MPLab%20X%20IDE/25.png "selected XC8")

Now would be a good time to set your build folder also.

Select Building on the left

![alt text](https://github.com/RShankar/Intro-to-Microprocessors/blob/master/MPLab%20X%20IDE/18.png "Building")

Finally add __cp ${ImagePath} YOUR PATH HERE__ to the execute this line after build field and check the check box. C:\Users\Doug\Desktop\HEX is the path used for this example.

![alt text](https://github.com/RShankar/Intro-to-Microprocessors/blob/master/MPLab%20X%20IDE/19.png "Add Path")
