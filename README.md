# Teaching with Maps

This repository contains a mapping classroom activity. It was designed for a college digital humanities course, but it has applications across a variety of humanities and data-oriented courses. Feel free to adapt and circulate!

# The Activity

I wanted students to think about how data sets are constructed and shaped by the choices and priorities of the researcher. I also wanted them to think critically about how we clean our data. (A list of some related readings that they did prior to this class are below.)

I set up a digital map using Leaflet, a JavaScript library that allows you to create custom maps using just a spreadsheet. That template is in this repository, and you can clone and customize the template. I also created a spreadsheet to house spatial data. (You can access that template here: https://docs.google.com/spreadsheets/d/1SUfcfBPWb5V2ff3-Yd2YvLMl_T5xZBbtdAMoQn4Az0c/edit?usp=sharing) Before class, I made sure the map was live and pointed at the spreadsheet. I pulled it up with just my sample data point in it to show them what we'd be working with.

In class, I began by asking them to create a spatial data set. In my Intro to Digital Humanities class, which I structure around local history and culture, that entailed mapping places that they thought of as cultural landmarks. It could be anything, though - places referenced in a particular work of literature, significant sites related to a particular historical event, or anything else with a spatial dimension. I gave them about 15 minutes to find and encode their place(s) in the spreadsheet. 

Once the spreadsheet was populated with some entries, I refreshed the map. When you do this, it will almost certainly break and display no entries, even your sample point. That's because they'll have very likely introduced formatting issues in their coordinates. Some might have copied the coordinates in with the degree symbol rather than as decimals. Others might have accidentally copied bolded text, extra characters - any number of issues. It's actually good if it breaks! That gives us an opportunity to talk about data cleaning for machines. One of the reasons we clean our data is to make sure that it's machine readable - that is, that it's in the format the computer expects. 

Once we saw the broken map, I went through and cleaned up the coordinates. Make sure that they're all in decimals (38.639444, -90.283333) rather than minutes and seconds (38°38′22″N 90°17′40″W). If everything looks ok and it's still not working, you can also highlight both columns and hit Format > Clear formatting to make sure there's nothing hidden in the text. It might take a minute or two for the changes to take effect and reflect on the map. (If all else fails, remove all but the cleanest looking entries - with Google Drive's version history, you can always restore what you've deleted.)

When the map was functional, we made some observations about the distribution of the points. Ask them to think about where the clusters are and what gaps remain - do those indicate a lack of sources, or a lack of attention by the researchers (them)? In what other ways are their choices evident in the map? How were they constrained by the columns on the spreadsheet (that is, by your/my choices)? If they were creating the spreadsheet, what columns would they create, and what categories would they impose on their data?

This activity helps them to think about where data comes from, how it's shaped by computational/technical needs, and how it's shaped by the needs and priorities of the researcher or project. If you use it, feel free to reach out and let me know how it goes!

# The Technical Details

I've set this up to hopefully have as low a technical barrier as possible. 
