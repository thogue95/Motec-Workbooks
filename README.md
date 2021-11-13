# Motec-Workbooks

You might see these in action on the YouTube channel: https://www.youtube.com/c/BustersCorner

You will see I have shared two Motec Workbooks that I created to use with the Iracing telemetry. You will see that I used the workspace pull down to be a vehicle selector and the worksheets to be the areas of focus.  Unfortunately, Iracing and Motec are making it difficult when it comes to Shocks vs Dampers and using them in the Suspension Histogram. Iracing has chosen to send NextGen shock positioning telemetry and Truck shock positioning on different channels. Motec for some reason has their Suspension Histogram calculations in a single workbook can only be either a Shock or a Damper (programmers language is that the calculation is scoped across entire workbook).  Since Trucks and NextGen don't both use shocks, they can not exist in the same workbook.  When Iracing and Motec get this resolved I will try to update the workbooks so we can get one workbook instead of two.


Here is a sample Overview Screen for the NextGen.

![Motec Overview](https://user-images.githubusercontent.com/8271391/141644352-e0d89e26-42e2-4067-8cad-02168c2f8de2.png)


As you walk through the screens, you will see a Downforce waveform.  The downforce is calculated for Trucks and NextGen cars using estimated wheel bases and body surface areas. 
Tip: For those people running late models, you can use the calculations in Maths as a starting point to create the functions you need for your cars.  Late Model usually runs on shorter tracks so not sure if downforce is all that useful.  

Enjoy and have fun!!!

Installation:

You must have Motec installed.  If you don't, then you will need to go research it.  Good place to start is here: https://boxthislap.org/how-to-use-motec-on-iracing/

Once Motec is installed, then download the zip files and extract.  Move the extracted directory to: C:\Users\tom_h\Documents\MoTeC\i2\Workspaces

Run Motec.

Tip:  Motec REALLY wants to see loaded data.  This gets me every time still!!!  
