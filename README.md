# Data Visualization in Tableau

**CREATE A CHART**

1. Log in to Tableau Public. 
2. Go to your profile. Hover over the circle in the upper-right corner and click **My Profile**.

![home page](https://user-images.githubusercontent.com/3311519/178914751-7b7fe3e0-e3a1-4d39-82fd-c019fe557788.png)

3. Under the Getting Started header, click **Create a Viz**.
4. This may bring you to the **Connect to Data** window. If so, go to the **Files** tab and open the **CO2 dataset** you downloaded earlier. If not, navigate to the **Data** tab at the top of Tableau Public interface. Under the dropdown, click **New Data Source**. Then open the CO2 dataset here--> [CO2-Dataset.xlsx](https://github.com/amanz/Tableau/files/9109128/CO2-Dataset.xlsx)
5. Once you have uploaded the data, you will notice the following display. Locate the sheets contained in the data file on the left side of the screen.

![1st](https://user-images.githubusercontent.com/3311519/178917890-6ed75769-f583-4a7d-9784-0af3e8d90d72.png)


6. Double-click on the sheet **CO2 Data Cleaned** to load that sheet's data into the main part of the screen. You can also drag and drop the sheet into the area where it says **Drag tables here**. Once this is done, the main display will appear like this:

![2nd](https://user-images.githubusercontent.com/3311519/178917370-36a2aec1-2638-4ce3-aa86-0404c1ff2c96.png)

The data in the table are listed in the bottom portion of the display above. By default, Tableau will only show the first 1000 rows in the table, but you can increase the number of rows in the settings above the data view.

Each row corresponds to a single data point, and each column represents a different feature.

Tableau interprets the type of data in each column. The following icons, which are above in the column name, refer to how Tableau interprets the data type in the column:

**#**: Numeric data

**Abc**: String data

**Globe**: Geographic data

**Calendar**: Date data

**Calendar with a clock**: Date and time data



**CREATE A VISUALIZATION OF CO2 EMISSIONS**

Now that you have all of your data loaded into Tableau, you can use it to make visualizations. Create a visualization in which the CO2 emissions are displayed per country.
To do this, click on the **Sheet1** tab in the lower-left of the display.

![3rd](https://user-images.githubusercontent.com/3311519/178918664-a8c68e39-4da3-4dc0-950b-f7793a84c778.png)

Clicking this tab will change the display to this:

![4th](https://user-images.githubusercontent.com/3311519/178920156-8ccdca2c-419a-4a8d-95f3-326218b43496.png)

**Use dimensions and measures**

On the far left of the screen is a banner with column names above a grey line. In Tableau, these are called the **dimensions** of the data. Below this line are the different **measures** that you can track for these dimensions. 

Now, create a chart that displays the CO2 emissions per country. Double-click the **Country Name** dimension. The main display will show a map of the countries on the planet with dots indicating which countries are represented in the data.

![5th](https://user-images.githubusercontent.com/3311519/178921064-2af31d0b-387a-4ab3-813c-46cc6f48fea6.png)


The dots are all the same size because—with no measure selected—Tableau defaults to scale each country equally. If you want to scale by CO2 emissions, you need to include a specific measure.

Double-click (or drag and drop onto the sheet) the measure **CO2 (kt)**. This will change the size of the dots to be proportional to the amount of CO2 emitted.

Tableau has a wide selection of options for depicting the measure for a given dimension. Most of these options are contained in the middle column between the main display and the column with dimensions and measures.

![6th](https://user-images.githubusercontent.com/3311519/178921661-012666cf-ec3e-4682-920c-aa4acdcddeeb.png)


**Customize your chart**

If you drag and drop a measure on one of the option classes, such as Color, Size, and Label, you can change that aspect of the measure’s visualization on the chart. 

For example, if you want to change the color of the CO2 measure, drag the measure **CO2 (kt)** to the box with the Color label. Then, click on this box to pull up a list of options for the colors you can use.

Play around with the different options here to learn what you can do. Don't worry about making a mistake. If you ever want to reverse a change you make to a Tableau sheet, you can hit the **Back arrow** button in the top-left corner of the screen:
![7th](https://user-images.githubusercontent.com/3311519/178921992-df465385-e306-4387-8c7f-ad2da5443956.png)


**Change dimensions and measures**

Changing either the dimension or the measure on a chart is very easy to do. Suppose that instead of visualizing the CO2 per country, you want to chart the CO2 per capita per region. To do this, double-click on the dimension Region and then do the same for the measure CO2 Per Capita. This will result in a new chart like the example below:

![8th](https://user-images.githubusercontent.com/3311519/178922887-f9a4e9db-c71b-4995-9cdc-cf961f205e23.png)


**Edit the title**

Currently, the title of this chart is Sheet 1. To edit the title of the chart:

1. Hover the cursor over the title box. An arrow will show up in the upper-right of the box. If you do not see the arrow on the upper-right of the box, make sure to close any panels on the right of your screen or double-click Sheet 1 to change the title. 

2. Click on this arrow to bring up a drop-down menu. Select Edit Title.

3. Enter any title you wish.

**Delete a chart**

If you want to delete a chart from the sheet, select the Clear Sheet button in the toolbar.
This will completely wipe out the chart and bring you back to an empty sheet. Don't worry if you do this by accident or change your mind. The **Back** button introduced earlier will bring the chart back.

If you want to delete a sheet in its entirety, all you need to do is right-click on the sheet's tab at the bottom of the screen and select **Delete**. Note that you will not be able to delete a sheet if it is the only sheet in your file.

**Note**: Unlike clearing a sheet, deleting a sheet altogether cannot be reversed!





