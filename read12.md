# canvas


*(canvas) element is used to draw graphics, on the fly, via JavaScript. The canvas element is only a container for graphics. You must use JavaScript to actually draw the graphics. Canvas has several methods for drawing paths, boxes, circles, text, and adding images.*



!<!canvas id="myChart" width="400" height="400"><!/canvas!>
<!script>
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        });
<!/script!>!


The (canvas) element has only two attributes:
1.  width 
2.   height.


# fallback content: 

content that is to be used when the external resource cannot be used ,

<!partially supported element>
<!fallback>
insert fallback content as it doesn't work in IE
<!fallback />
stuff for new browser
<!partially supported element />

<!stuff for visual users non-visual="stuff for assistive
technology">Stuff for visual users<!stuff for visual users />

-------------------------------

# chart.js

It's easy to get started with Chart.js. All that's required is the script included in your page along with a single node to render the chart.

Contributing Before submitting an issue or a pull request to the project, please take a moment to look over the contributing guidelines first.

page and import the script:
+`` <!DOCTYPE html> + <html lang="en"> + <head> + <meta charset="utf-8" /> + <title>Chart.js demo</title> + <script src='Chart.min.js'></script> + </head> + <body> + </body> + </html>``


