# MDM-Game-of-Life
HTML5 Implementation of John Conway's Game of Life for MDM Greeter

To change any of the basic settings such as:
  - the number of Columns
  - the number of Rows
  - the space between tiles
  - or the colour of live and dead tiles
  
then this involves editing the index.html file.

1. In the index.html file locate the javascript "properties" object
2. You may edit any of the variables under the editable comment
   but be warned,
   
   a. if the tile colours are edited then the GOL.css file located in
     the CSS folder should also be edited to complement these colours.
     
     i.e- 
      if the tileDead property is changed to white (#FFFFFF) then in the CSS file 
      the Background colour should be changed to white, and the text colour
      should be change to black.
      

ISSUES-
  - if you notice any performance issues please follow the above steps and choose a
    smaller grid size
    
    i.e-
      tileCols: 20,
      tileRows: 20,
