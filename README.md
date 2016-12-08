For this project, we created a Web App that enables the user to find out the winners of 
specific Oscar awards between the years of 2000 and 2015.

This tool was intended to serve film industry lovers and answer their questions on the most popular awards presented at each year's Oscar ceremony.

It is important to be aware that the Oscars held in 2016 are awarded to movies created in the previous year (2015).

For example, the Best Picture at the 2016 Oscars was "Spotlight". However, this movie was actually produced in 2015.

For our Web App, the input of "Year" is the actual year in which the film was produced (and then presented at the next year's Oscar ceremony).
Within our Web App, if you input "Best Picture" and "2015" the output will be "Spotlight".

To create this Web App, we installed the following packages: wtforms and flask. Wtforms is used on the homepage of the Web App to request the inputs of year and award.
Flask is used to output the results of the specified function onto a webpage.

-------------------------------------------------------------------------------------------------------------------------------------------------------

The way the code runs is once the user inputs a "year" and "award type", the program searches within the appropriate dictionary and returns the appropriate value
or "winner". These Python functions are then intertwined within our HTML files so that the results of the executed function are presented in the website that we created.
The design of our HTML is catered to capture the environment of the Oscar Award Show. 

If an invalid input is entered by the user, a result of "None" will appear, which is why it is clearly stated that the only valid entries are within years 2000 to 2015.
We restricted the input years because we wanted to capture the most recent award winners within the past decade - capturing the movies and actors that our age group would easily recognize
and be able to relate to.

The certain awards that we provided are the following:

- Best Actor
- Best Actress
- Best Supporting Actor
- Best Supporting Actress
- Best Director
- Best Animated Feature
- Best Picture
- Best Original Song
- Best Original Score
- Best Visual Effects
- Best Original Screenplay
- Best Adapted Screenplay

The "main" function provided at the bottom of of the "oscar_winner" python file serves as test code to see if the results are accurate and if the functions are being executed correctly.

So, have fun testing out our app and building your love and knowledge for the most acclaimed award ceremony in the film industry!

