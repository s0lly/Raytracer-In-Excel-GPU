# Raytracer-In-Excel-GPU
Raytracer in our favourite spreadsheet application, using the GPU!

NOTE: For this model to work, you  need to include the Excel Add In "Excel GPU Demo Raytracing.xll" via the "Options->Add-ins->Excel Add-ins" menu, and have the shader in the following file path: C:\Excel XLLs\Raytracing\shaders\
See the accompanying video to set up the model and add-in correctly: 
NB: If the add-in is not working (i.e. is crashing Excel when Excel opens), it can be disabled by opening a blank workbook and disabling the add-in in the "Options->Add-ins->Excel Add-ins" menu

Summary

This excel file demonstrates using the GPU through Excel. The GPU is able to handle vast numbers of calculations per second, and what better place to throw calculations at the GPU than through Excel?
The Excel Add-In includes a number of functions that demonstrate this usage. This file only demonstrates the "RaytraceImage" function.
The raytracing algorithms used are largely based on that used in the book "The Ray Tracer Challenge" by Jamis Buck. It is an excelllent book that teaches the foundations of Raytracing in a fun and engaging way.


Instructions:

First, you need to go to the sheet named "Screen". Next, you need to run the macro called "Play" - you can do this using the "PLAY" button.

This macro assigns new functionality to the following keys:
 - "w", "a", "s", "d": press these to move the camera forwards, backwards, and sideways
 - "r", "f": press these to move the camera up and down
 - "u", "i", "o", "j", "k", "l": press these to rotate the camera along the 3 different 3d axes
 - "esc": press this to end the game and reset all key functionality

NOTE: this macro overrides these key's normal functionality - you must press ESC at the end of your session to reenble these keys in excel to their original functionality

Alternatively, you can press the "ANIMATE" button which will move the camera along a predetermined path.


by s0lly
https://www.youtube.com/c/s0lly
https://www.instagram.com/s0lly.gaming/
https://twitter.com/s0lly
https://https://www.twitch.tv/s0llygaming

THE MODEL AND EXCEL ADD-IN ARE PROVIDED WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.

