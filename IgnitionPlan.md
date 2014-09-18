###Ignition Plan; 5 Year Ignition Data
####(WorkingDoc.)
___

#####Purpose
The 5 Year Ignition Data is used in FDOD to help visualize vegetation fire occurrence in San Luis Obispo. This graph is created using an excel spreadsheet. The main aspect of this graphic is to display the cause totals by percentage.
#####Location
						C://_projects/Ignition_Plan/5 Year Ignitions(SLU)2009_2013 

#####Working with the Fire Data
This excel document houses the fire data required to create the table, the pivot charts used to create the graphics, and graphics used in the document. Export the fire data for the date range necessary to update FDOP using the WebRPT site credentials (Refer to the [FDOP](http://slocountyfire.org/FDOP/) website under the 'Fire' section for directions to export fire data).  

#####Using Pivot Tables

The Pivot Table button may not be a default button of excel. My Pivot Table button exists i the Insert Ribbon. If it itsn't there ... GTS.

- Insert> Pivot Table> Pivot Table>
	- In the 'Create PivotTable' dialog box select the 'Select a table or range' radio button. The cursor should be blinking in the 'Table/Range:' field - now, select the column you want to work with. In this case, you can select two columns by cicking and dragging across the top of the two. 
	- In the 'Choose where you want the PicotTable report to be place' sections select 'Existing worksheet' and then click the location of the work sheet that is most appropriate for your table to exist. 
	- Select 'Ok'
	

	
#####Tips and Tricks	
'Create PivotTable'
- once an edit has been made to the placement of a label (annotation style) select the Pivot Graph then right click, 'Format Data Labels'

#####Creating the Graphics 

A Pivot Graphic is created and used in the same way that a Pivot Table is.

- Activate the graph by clicking anywhere inside the graph. You will see the Pivot Table Field List. When doing tis for the first time it may open up in a separate window - you can dock this dialog box on either side of excel. This field box consists of 5 sections. 'Cause' and 'Year' should be listed in the 'Axis Fields'. 'Count of Cause' should be listed ien the Sum Values field.  
- You can filter out and customize to a more detailed degree by selecting the filter icon next to each participating fields in the main 'Choose fields to add to repot:' dialog. 
- Activate the Pivot Graphic > select the pie chart itself > right click the chart > select 'Format Data Labels'. In this dialog box you have the opportunity to adjust and edit the labels of the graph. In my experience I have found that the best wy to display theis informatio is to enable 'Category Name', 'Percentage', and 'Show Leader Lines' (all of this can be done in the Label Options section). In the Label Position section select 'Best Fit', then adjust labels individually if needed.
