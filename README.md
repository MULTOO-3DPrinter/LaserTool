# LaserTool

- Laser engraving function of 3D printer
- This is an auxiliary software. The main function is to export files recognized by the 3D printer (NC, Gcode, and other formats).
- The exported file format can be customized. What it exports is text.
- It only does image processing.
- This software is mainly provided to customers who own MULTOO 3D printers. Customers can also choose not to use it. 
- It is a security software, please feel free to use it.
&nbsp;



## 

- [Version3.1](#version3_1)
- [Version3.0](#version3_0)
- [Usage](#usage)


&nbsp;




<span id = "version3_1"></span>
## Version3.1

- Fix calculation bug
- 'Help' display content correction
- The maximum engraving size is restored to the original setting of 400 (mm) * 400 (mm).

&nbsp;





<span id = "version3_0"></span>
## Version3.0

Compared to all previous versions,
- Added filtering of images
- Increase inverse color
- Added custom area carving
- Removed the text edit box
- The engraving size is temporarily set to 200 (mm) * 200 (mm).

&nbsp;



## Usage

1. Engrave the image.

Import the image file into LaserTool and export the nc file.

`Image` -> `LaserTool` -> `nc file`.


![Image](https://github.com/MULTOO-3DPrinter/LaserTool/blob/22f24202218b236eb1e4903bc263fe9470a5a678/images/2.png)






2. Character engraving.

Edit the text in inkscape, and then export the png format image. Change the format of the png format image to jpg, bmp, jpeg, etc., and then import it into the LaserTool and export the nc file.

`Edit the text in inkscape` -> `png file` -> `jpg, bmp, jpeg etc.` -> `LaserTool` -> `nc file`

**To convert png to bmp or jpg format, you can use the ‘Edit’ tool in the right-click menu of the Window system.**

![Image](https://github.com/MULTOO-3DPrinter/LaserTool/blob/e70e9f90d849fed1870f93785b2d43514e641d02/images/text.png)


