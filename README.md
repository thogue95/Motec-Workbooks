# Motec-Workspace
Update: 12-3-23:  
Changing the version naming to include a year and season time stamp.  
Updated the Overview worksheet, added Driver worksheet, removed Aero worksheet, corrected Diffuser Wedge calculation to reflect trend to run negative rakes, updated Tire Temps to include tire pressures and pressure staggers, added Tire Stint Heatmaps and updated Slip and Spin worksheets.
Removing Version 8.1 as iRacing changes have made somem of the worksheets inaccurate.

See video on Busters Corner for a detailed walkthrough of this update.
https://www.youtube.com/@BustersCorner

Update: 3-17-2022: Removing older version Next Gen V7.6 to encourage people downloading the most current.

Update: 3-12-2022: Some users were seeing the Steering Wheel not rendering the angle correctly.  This was fixed by setting the Wheel range to manual with min and max values set to -90 and 90 respectively.  V8.1 has that correction.  V8.0 is removed.

Update 3-11-2022: v8.0
New Slip and Spin worksheets added to give Car Side Slip Angle, Front Slip Angle, Rear Slip Angle and improved Wheel Spin worksheets.  Improved the Tire Track Reports with consistent color scales for easier interpretation.  These worksheets should provide better insight into loose conditions and give information needed to get more speed and stability out of the setups.  Most of the new screens have been designed to make it easier for most people to be able to use the telemetry without being an engineer while still keeping technical screens available for those that enjoy the technical approach.

Removing Next Gen v7.2

As usual, you will most likely will not understand what you are looking at without watching the video as in the video I explain the concepts behind the new worksheets.  Here is the link to the video.

https://www.youtube.com/watch?v=MigyRSuNbB8

Tip: When you identify a problem, look at the timing of the problems.  Identify the problem that occurs first and chase that down first.  


Update 2-16-2022:  Updated the Truck and Xfinity workbooks to v7-6.  While Busters Corner videos are focused on NextGen cars, I would strongly encourage watching the videos where these workbooks are discussed.  Especially the shock video and the Motec video so you can understand the color coding on the shock and roll velocities.  Removing the older Truck v5 version.

READ THIS:  The garage tab is intended to give you reference to how the car is setup so you don't have to write on a note pad.  This information is just read and displayed using the MoTec conversions.  There are several numbers that look off or incorrect.  This is not my doing.  It is due to iRacing or MoTec improperly doing conversions.  I suspect more on the issue is more on the iRacing side, but was not worth the time to investigate.  Either way the numbers will get you close enough to recreate the setup if you change settings without saving your setup config.  In summary, don't blame the messenger!  :-)


Update: 1-30-2022:  New Workbook v7-6.  Created new Track Views, Roll Histogram and updated some elements in the garage.   New Track Views are a big change and adds significant context.  Detailed explanation is given in a video on Busters Corner YouTube channel.  I encourage all to watch it to understand how to use the new Track Views.  https://www.youtube.com/watch?v=vXgJ65A6F40

Update 1-21-2022: Found some conversion errors on the Garage Worksheet and some of my development artifacts on someof the other pages.  Those that are watching your roll bar preloads will appreciate this update.  Removing v6-2, v7-1 as well as NextGen and Tours Ver 5-2.

Update 1-19-2022: Updated the NextGen workbook to Version 7-1.  Added a Diffuser Worksheet and a Garage Worksheet.  Added Brake Pressure to the Wheel Spin Page.  You will need to watch the video on Busters Corner to understand how to use the Diffuser Worksheet.  Garage Worksheet is the values from the Garage as well as a Center of Gravity Scatter Plot.  See pics below.

https://www.youtube.com/watch?v=oYLktIN5GoA


Updat: 1-1-2022: Just completed a video going over the V6-2 in detail.  https://www.youtube.com/watch?v=Lm5fUQlViJs

Update 1-1-2022: Corrrected Compression and Rebound signed values in v6-2 for both NextGen and SK/Tour cars.

Update 12-30-2021: New versions of my Motec Workspace for NextGen and the Sk and Tour Modifieds.  Sorry Trucks, no update for you.  These are verion numbered at v6-1.  There is a Dyno page in there on both workspaces and the NextGen has significant updates for shock tuning.  You will not get the value out of the shock pages unless you have watched the video referenced below.  Other minor tweaks and clean up as well.

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

Difuser Worksheet: 
![Diffuser Page](https://user-images.githubusercontent.com/8271391/150249281-4fda4860-d46e-4b64-a08e-0d5d8b1c2a2f.jpg)


Garage Worksheet:

![Garage Page](https://user-images.githubusercontent.com/8271391/150249363-1f0bba33-701f-4d9a-ad52-af3d4674521f.jpg)




