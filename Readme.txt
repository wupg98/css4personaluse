index.html 
What we still need is an automatic launch of the loading.
These are really great ressources on learning how to click links via JS and simulating the click event:

https://www.geeksforgeeks.org/how-to-simulate-target_blank-in-javascript/


https://www.geeksforgeeks.org/how-to-simulate-a-click-with-javascript/

https://codingbeautydev.com/blog/javascript-simulate-click/#:~:text=click()%3B,it%20to%20simulate%20the%20click. 
https://stackoverflow.com/questions/2705583/how-to-simulate-a-click-with-javascript
=>DONE.
10.08 (see commits)
02.12 (temp)
commented out
      
           // document.getElementById("input1").click();
   
    //    document.addEventListener("click", function(e) {
    //        if (e.target.tagName == "A" &&
    //                !e.target.hasAttribute("target"))
    //        {
    //            e.target.setAttribute("target", "_self");
    //        }
    //    });
22.08
Also   <!--<meta name="robots" content="nofollow" > --> 
needs the comments removed once indexing worked.


nojs.html:
Now a link gets loaded is js is deactived with instructions and hint to download the pdf document instead and mail it in.
In case js is activated load the previous page and dont show the instructions
due to a js script used here (for pure documentation:
)https://stackoverflow.com/questions/2554149/how-can-i-change-div-content-with-javascript
Would have been more beautiful if it would load the pdf or download it without js but I guess since its about usability of the user this fits best.
And the formular cannot be typed in anyhow so its good how it is. And since this is for mobile devices the alternative(only working in Internet Explorer was osbolete).
JS  currently removed so visitors through search engine still get to see nything.
=>DONE

22.08:
nojs.htm
(replica but without canonical <!--<link rel="canonical" href="https://letsstopawar.eu/index.html" /> -->)
all the same stuff as with nojs.html needs to be considered.

mycss.css: 
he intention was to use it for iframes or h1
but in case Im bored I might play abit round with it for example for the link stylings.
https://stackoverflow.com/questions/7896402/how-can-i-replace-text-with-css
https://www.freecodecamp.org/news/css-background-image-with-html-example-code/
xml/letsstopawar.xml:
Added RSS feed
for improvement in search results via rss feed

https://yandex.ru/support/webmaster/search-appearance/news.html


Für mail eventuell (contact):
https://developer.mozilla.org/en-US/docs/Web/CSS/::after?retiredLocale=de

Other stuff:
For users with webserver knowledge: the xml file and the yandex are for SEO of the Bing and Yandex Search engine that are independant of Google.
Google SEO data was added directly at the DNS providers.
Yandex first
Google second showed up in results-
Yandex due to recrawling currently not listing the domain anymore.
