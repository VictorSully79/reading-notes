# Charts with JavaScript

### Charts display information in a more visually appealing and readable way.  Basic 3 graphs:
- line chart
- pie chart
- bar chart

### Charts require the download of Chart.js then adding the script to the body of the HTML to import the data. Example:

``` 
  <script> var buyers = document.getElementByID('buyers').getContext(2d);
  new Chart (buyers).Line(buyerData);
  </script>
  ```
  # Shapes with JavaScript

  ### On the Canvas 1 grid equals 1px. Examples:

  - `fillRect(x, y, width, height)` Draws a Rectangle

  - `strokeRect(x, y, width, height)` Draws a rectangular outline

  - `clearRect(x, y, width, height)` clears the specified rectangular area, making it fully transparent

### Paths, triangles, lines, arcs, bezier and quadratic curves and many other items can be drawn.  The color of these can also be altered.