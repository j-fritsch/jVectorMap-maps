jVectorMap-maps
===============

Maps included:  

  - Africa
  - South America
  - Asia (including Singapore).
 
This also includes a guide on how to make maps.



Small Countries
---------------

A problem with some countries is their size. Some are just too small to be represented and are therefore not picked up by the jVectormap Converter. The developer suggests using [markers](http://jvectormap.com/examples/markers-world/) in the place of the countries, but depending on the project, that may not suffice.

One way to get around this is by generating these smaller countries by themselves - just smaller! For Asia, I needed Singapore on the map. This was accomplished in four semi-easy steps.

 1. Generate a map of Asia
 2. Generate a map of Singapore
 3. Copy the Singapore code into the Asia code
 4. Move Singapore to the correct position

When generating a map, you can give it any width you want. For Singapore, I used a width of 2.5. This gave me a small enough map of Singapore. It didn't look _great_, but it worked. It gave me something to hover over and click on.

After generating the map, I copied the code that made up the map of Singapore and pasted into the map of Asia. The next problem was the placement of Singapore. It wasn't in the correct spot on the map. The first two numbers in the "path" section are the coordinates that determine the placement. Changing those made it move up, down, left, and right. I got it in a place that was good enough and there I had it, a map of Asia - including Singapore.
