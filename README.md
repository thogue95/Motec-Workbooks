# Motec-Workspace

Update: 12-30-2021: New versions of my Motec Workspace for NextGen and the Sk and Tour Modifieds.  Sorry Trucks, no update for you.  These are verion numbered at v6-1.  There is a Dyno page in there on both workspaces and the NextGen has significant updates for shock tuning.  You will not get the value out of the shock pages unless you have watched the video referenced below.  Other minor tweaks and clean up as well.

Update: 12-27-2021: There is a new video that you will want to watch to see how to interpret those suspension histograms.  This will also provide a foundation for a new workbook I will be releasing soon that will provide a new view into suspension telemetry.  https://www.youtube.com/watch?v=gIC7VF8aG34

Update 12-3-2027: Here is an install video: https://www.youtube.com/watch?v=5OCwlHEV5FM&t=16s

Update: I have started to come back and do some updates to these workbooks so you will start to see additional version numbers.

12-3-2021: NextGen and Tours Ver 5-2.  Cleaned up some of the screens and adjusted some scaling of data in bars.

Original Post: 
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
