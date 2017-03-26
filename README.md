## Website Performance Optimization portfolio project


->Initial Page Insights Score of index.html is 27/100
->After optimization : 94/100


##Replaced font ( href="//fonts.googleapis.com/css?family=Open+Sans:400,700" rel="stylesheet) with inline script
 [
  WebFontConfig = {
            google: {
                families: ['Open+Sans:400,700']
            }
        };
        (function() {
            var wf = document.createElement('script');
            wf.src = ('https:' == document.location.protocol ? 'https' : 'http') +
                '://ajax.googleapis.com/ajax/libs/webfont/1.5.18/webfont.js';
            wf.type = 'text/javascript';
            wf.async = 'true';
            var s = document.getElementsByTagName('script')[0];
            s.parentNode.insertBefore(wf, s);
        })();
]

##Resized & Compressed Images

Pizzeria.jpg & Profilepic.jpg - Compressed to 75% smaller which had huge impact for optimizing.


##Cached
Added no-cache meta to the page

##async

Added async attribute to javascript files

##CSS
Replaced CSS file with Inline CSS IN Index.htmls
added media type so CSS will be rendered only when necessary


Replaced Images with resized Images

Optimized the loops contained in the updatePositions function and the onDOMContentLoaded event handler.

Optimizes Animations with requestAnimationFrame to call updatePositions on scroll

Also updated onDOMContentLoaded event handler



References & Resources:

#Page Insight Score: https://developers.google.com/speed/pagespeed/insights/

#Caching - https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching

#Optmizing Images

https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization

Image Compressor - https://tinyjpg.com/
Image Resizer - http://picresize.com/

https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads

https://www.html5rocks.com/en/tutorials/webperformance/usertiming/

https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript

