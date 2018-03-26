EXIF Removal tools are hard to come across, in non-online / sketchy program form.  
  
Not being careful about it has got people caught in the past - [https://gizmodo.com/5901430/these-breast...n-fbi-case](https://gizmodo.com/5901430/these-breasts-nailed-anonymous-hacker-in-fbi-case)  
  
This'll work on Linux, but I also like to use the Ubuntu for Windows Terminal on my Windows machines to remove EXIF over there too.  
  
First of all you're going to need to install 'exiftool'  
  


`admin@crypt-fi:$ sudo apt install exiftool`

  
Now you'll want to CD into the Directory that your image is saved in if you're using the Ubuntu for Windows Terminal cd /mnt/ and navigate your way from there.  
  


```
admin@crypt-fi:$ cd Example  
admin@crypt-fi:/Example$ ls  
  
DSCN0010.jpg
```

  
Now we're going to run a command to remove all exif for a specific file, if you'd like to remove EXIF for all files in a folder do *.jpg  
  


```
admin@crypt-fi:/Example$ exiftool -all= DSCN0010.jpg  
  
    1 image files updated
    
```

  
  
Here's the Example file I used: [https://raw.githubusercontent.com/ianare...CN0010.jpg](https://raw.githubusercontent.com/ianare/exif-samples/master/jpg/gps/DSCN0010.jpg)  
  
Has plenty of EXIF, which you can view beforehand to check this works.  
  
  
To view the EXIF / Metadata of a file we'll simply do:  
  


`admin@crypt-fi:/Example$ exiftool DSCN0010.jpg`

  
To edit the EXIF / Metadata of a file we'll do:  
  
 

`admin@crypt-fi:/Example$ exiftool -all=test DSCN0010.jpg  (This will set every writable piece of exif to display 'test')`

  
or if you want to edit a specific piece of exif:  
  
 

`admin@crypt-fi:/Example$ exiftool -Copyright=Sock DSCN0010.jpg`

  
Use 'apostrophes' if you're writing more than one word.  
  
You may also want to look at MAT - [https://github.com/jubalh/MAT](https://github.com/jubalh/MAT)   
  
Here's the EXIF Data before we ran EXIFTool:  
  

```
File Name                       : DSCN0010.jpg  
Directory                       : .  
File Size                       : 158 kB  
File Type                       : JPEG  
File Type Extension             : jpg  
MIME Type                       : image/jpeg  
Exif Byte Order                 : Little-endian (Intel, II)  
Image Description               :  
Make                            : NIKON  
Camera Model Name               : COOLPIX P6000  
Orientation                     : Horizontal (normal)  
X Resolution                    : 300  
Y Resolution                    : 300  
Resolution Unit                 : inches  
Software                        : Nikon Transfer 1.1 W  
Modify Date                     : 2008:11:01 21:15:07  
Y Cb Cr Positioning             : Centered  
Exposure Time                   : 1/75  
F Number                        : 5.9  
Exposure Program                : Program AE  
ISO                             : 64  
Exif Version                    : 0220  
Date/Time Original              : 2008:10:22 16:28:39  
Create Date                     : 2008:10:22 16:28:39  
Components Configuration        : Y, Cb, Cr, -  
Exposure Compensation           : 0  
Max Aperture Value              : 2.7  
Metering Mode                   : Multi-segment  
Light Source                    : Unknown  
Flash                           : Off, Did not fire  
Focal Length                    : 24.0 mm  
Maker Note Version              : 2.10  
Color Mode                      : Color  
Quality                         : Fine  
White Balance                   : Auto  
Focus Mode                      : AF-S  
Flash Setting                   :  
ISO Selection                   : Auto  
Face Detect Frame Size          : 320 240  
Faces Detected                  : 0  
Active D-Lighting               : Off  
Image Adjustment                : Normal  
Tone Comp                       : Normal  
Auxiliary Lens                  : Off  
Digital Zoom                    : 1  
AF Area Mode                    : Single Area  
AF Point                        : Center  
AF Points In Focus              : (none)  
Scene Mode                      :  
Distortion Control              : Off  
Noise Reduction                 : Off  
Scene Assist                    :  
Retouch History                 : None  
Image Stabilization             : VR-On  
Picture Control Version         : 0100  
Picture Control Name            : Standard  
Picture Control Base            : Standard  
Picture Control Adjust          : Default Settings  
Picture Control Quick Adjust    : Normal  
Brightness                      : n/a  
Hue Adjustment                  : n/a  
Filter Effect                   : n/a  
Toning Effect                   : n/a  
Toning Saturation               : n/a  
Nikon Capture Version           : COOLPIX P6000V1.0  
NEF Bit Depth                   : n/a (JPEG)  
User Comment                    :  
Flashpix Version                : 0100  
Color Space                     : sRGB  
Exif Image Width                : 640  
Exif Image Height               : 480  
Interoperability Index          : R98 - DCF basic file (sRGB)  
Interoperability Version        : 0100  
File Source                     : Digital Camera  
Scene Type                      : Directly photographed  
Custom Rendered                 : Normal  
Exposure Mode                   : Auto  
Digital Zoom Ratio              : 0  
Focal Length In 35mm Format     : 112 mm  
Scene Capture Type              : Standard  
Gain Control                    : None  
Contrast                        : Normal  
Saturation                      : Normal  
Sharpness                       : Normal  
Subject Distance Range          : Unknown  
GPS Latitude Ref                : North  
GPS Longitude Ref               : East  
GPS Altitude Ref                : Above Sea Level  
GPS Time Stamp                  : 14:27:07.24  
GPS Satellites                  : 06  
GPS Img Direction Ref           : Unknown ()  
GPS Map Datum                   : WGS-84  
GPS Date Stamp                  : 2008:10:23  
Compression                     : JPEG (old-style)  
Thumbnail Offset                : 4560  
Thumbnail Length                : 6702  
Image Width                     : 640  
Image Height                    : 480  
Encoding Process                : Baseline DCT, Huffman coding  
Bits Per Sample                 : 8  
Color Components                : 3  
Y Cb Cr Sub Sampling            : YCbCr4:2:2 (2 1)  
XMP Toolkit                     : Public XMP Toolkit Core 3.5  
Rating Percent                  : 0  
Aperture                        : 5.9  
GPS Date/Time                   : 2008:10:23 14:27:07.24Z  
GPS Latitude                    : 43 deg 28' 2.81" N  
GPS Longitude                   : 11 deg 53' 6.46" E  
GPS Position                    : 43 deg 28' 2.81" N, 11 deg 53' 6.46" E  
Image Size                      : 640x480  
Megapixels                      : 0.307  
Scale Factor To 35 mm Equivalent: 4.7  
Shutter Speed                   : 1/75  
Thumbnail Image                 : (Binary data 6702 bytes, use -b option to extract)  
Circle Of Confusion             : 0.006 mm  
Field Of View                   : 18.3 deg  
Focal Length                    : 24.0 mm (35 mm equivalent: 112.0 mm)  
Hyperfocal Distance             : 15.16 m  
Light Value                     : 12.0
```

  
Here's the EXIF after:  
   

```
File Name                       : DSCN0010.jpg  
Directory                       : .  
File Size                       : 143 kB  
File Type                       : JPEG  
File Type Extension             : jpg  
MIME Type                       : image/jpeg  
Image Width                     : 640  
Image Height                    : 480  
Encoding Process                : Baseline DCT, Huffman coding  
Bits Per Sample                 : 8  
Color Components                : 3  
Y Cb Cr Sub Sampling            : YCbCr4:2:2 (2 1)  
Image Size                      : 640x480  
Megapixels                      : 0.307
```
