# Enterprise-DNA-Report
The data consisted of four different unrelated datasets, so you know that means I needed to create at least a relationship between them.

I removed some duplicates and some columns I don’t need for the analysis and created a number of calculated columns.

After putting a number of visualization tiles on the board, I hit a roadblock with the shape map when I needed to show countries that generated more views on the map.

Apparently, PowerBi doesn’t have the world map in-built and you have to go look for it. After a day of searching for answers on the web and asking people, I got the fix — a JSON file of world counties needed to be uploaded manually.

Only for me to take another step forward and be hit by another problem. Now my dataset only had 2-ISO codes, some call it Alpha-2 codes, that is, two-letter country codes that are not showing on my shape map.

I solved this by importing a web table with a list of countries and 3-ISO codes and then merged the relevant columns with my existing geographical data, and voilà, my shape map came forth.
Enjoy!

# Tool used: Power BI
