# ImageProcessing_Mosic
Making Mosic function with CxImage

Algoritm
1. Get image size(width and height)
2. Find Steps for window shifting
  1) XStep = Width / windowSize
  2) YStep = Height / windowSize
3. Calculate average of pixels in window
4. Put the average value of whole pixels in the window
5. Shift the window to next step
6. Repeat 3~5 steps to whole windows

Caution
1. Exception handling : Edge of the Image
2. Loss of data (below decimal point)
