# Disney-Plus-Hotstar-Clone
Disney plus Hotstar clone using pure HTML, CSS and JS. 

Our clone is very similar to the original disney plus website. It is only one page(homepage) website. It has navbar and search box with cool click effect same as disney+ and it also has a slider or carousel with infinity or endless effect. Which was very hard for me to make at first. And after that we also have movie cards. With awesome card hover effect. And we have much more.

* File Structures : 
• data.js    : This file contain our movie slider data
• index.html : HTML structure and link CSS and JS files. Make sure you add data.js file before app.js. So that we can access the data in app.js file.
• app.js     : Our Carousel element and created an empty array to store all slides. also create a function createSlide for creating a slide.
               In this function. In the start we are increasing or setting our next slideIndex with some if/else condition. And after that we are creating DOM 
               element   that we need for our slide. These all elements are exactly same as we had in our index.html.
               After creating all these elements. we can Append/attach these elements to one another to form the HTML strucuture.
               After done appending elements to each other. Now set their class names and set image's source.
               And last remember to push the slide inside sliders array.


If you see the starting data. You'll notice that our slide-1 is on second number on the list. Why is that. That is because. Our slider will have 3 slides at a time and we want the active slide to be in center. Which means when we first start with slide data. our active slide or first slide will be in middle. I hope this make sense.
We Have create these slides with JS.

This effect will only work if user click on your site first. If use did not click on your page first then the video will not play because of the google chrome policy.

❂ Hotstar Clone Demo UI View : ![Screenshot (334)](https://user-images.githubusercontent.com/104203768/219556390-e628b7c3-6314-4906-b2a3-1ce6a73035e1.png)

