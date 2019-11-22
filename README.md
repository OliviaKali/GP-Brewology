# [Check out the Brewology Website](https://oliviakali.github.io/GP-Brewology/)
## Brewology - "Don't Worry, Beer Happy!"

Brewology is an interactive app that connects beer and brewery information to the user based on their personality traits!

The User can take a quick five minute assessment that outlines the personality traits based on the Big5: 

<ol>
<li>Openness</li>
<li>Conscientiousness</li>
<li>Extraversion</li>
<li>Agreeableness</li>
<li>Neuroticism</li>
</ol>

The personality test results show which Big5 personality trait is dominant as well as recommend a beer that you might like based on that personality type.

If the user has already taken the personality test or doesn't want to, we provide an option to skip it altogether and just search for breweries based on the input location. 

## Built with
### API
<ul>
<li>Yelp API utilized to render brewery results based on the location input by the user.</li>
<li>Giphy API used to add a gif with the results from the personality test</li> 
</ul>

<!-- Yelp is not compatible with CORS so JSON response was pulled from proxy website (CORS-anywhere heroku) with yelp search endpoint attached to it
Yelp API passed through headers
Data used in the ajaxCall to keep the url string neater
UserInput used in on-click function so user can search any location and find breweries in that area
Yelp API defaults a return of 20 businesses- used for loop to return only 12 results
jQuery used to append results into card on html

Giphy IDs used so specific gifs are attached with the specific results -->

### Technologies Used

Website developed with HTML, CSS, and JavaScript.

Libraries used JQuery, Bootstrap, Materialize, and Font-Awesome.

## Team Roles

HTML, CSS - Emily & William
JavaScript - Vanessa & Olivia
   Personality Test - Vanessa
   APIs - Olivia

Team collobrated well while combining code to ensure functionality. 

<!-- ## Features

The personality quiz chooses a beer you might like based on your personality.
Yelp API is used to find nearby brewery's. -->

<!-- # Code

   # landing
   
Background image is set

A row is created to hold the Brewology logo in the center of the page

Two columns with nothing that take up two columns each they are surrounding the column with the links to the personality test and a link to look for nearby brewerys. The links are both in one column class and takes up eight columns. This keeps the link centered.

When the buttons "Location" and "Personality" are pressed they go to the same page. Personality brings you to the top of that page while location brings you to the bottom so the application so that the user screen displays the app they clicked on hthe top.   
 
   # index
   
Materialize, bootstrap, and fontawesone are linked.

Jumbotron creates the Brewology logo at the top.

Background image is set to the body.

The first row is created and holds the image at the top as well as uses bootstrap to keep it the full length of the that row's grid.

The next row with the personality test in it is made of one column using bootstrap to keep the text of the quiz centered.

The containers at the bottom beneath the text display yelp results.

   # personality
   
Questions for the quiz are created and listed as promps. Each prompt is made to measure a certain trait and each of the prompt_values (answer options) are given a weight of 1,2,3,4, or 5.

createPromptItems appends each question in a <p> tag placed in the ul with the quiz id.

   # personalty-response
   
Calculates extraversion trait by adding the first and sixth prompts.
Calculates agreeableness by adding the second and seventh prompt.
Calculates conscientiousness by addig the third and eigth prompts.
calculates neuroticism by adding the fourth and ninth prompts.
Calcualtes the openess by adding the fifth and tenth promps.
Each trait's final weight can be scored from a possible 2 to 10.
The highest trait is used to make the recommendation. Each trait is linked to a beer. -->


# Credits

Emily Betz, Olivia Kalinowski, Will Stark, Vanessa de La Cuetara, Anthony Sambogna
 
