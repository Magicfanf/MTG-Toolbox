# MTG-Toolbox
Apps to help improving Magic: The Gathering play
Feel free to reuse the code, or better, improve it and let me know!

thanks to Jamie Wilson for his article https://github.com/jamiewilson/form-to-google-sheets
and for Tanaike from stackoverflow.com who was so patient with me on https://stackoverflow.com/questions/64199227/parsing-a-stringified-json-coming-from-a-google-sheet-web-app

Home page
make 8 buttons available to the user to rate the cards
- they totally clash = -1
- they slightly clash = -0.1
- Not at all = 0
- By less than half a grade = 0.1
- By half a grade = 0.5
- By a full grade = 1
- By 2 full grades or more = 2
- I'm not sure... = 7

2 numbers from 1 to 265 are selected randomly. they are the set number of the cards to be displayed.
the images of the cards whose set numbers are the randomised numbers above are displayed below the buttons. the URL of the cards are coming from a Goolge Drive, where the image files are shared openly.

the user clicks on one of the buttons to provide a rating. the output of the app contains:
- the rating
- the set number of the 1st card
- the set number of the 2nd card


Results page

here, list of URLs pointing to images stored on Google Drive are provided in a sequence, which represent the ranking of the single cards/pairs in their category. the images are displayed on each line on their own or by pair.
