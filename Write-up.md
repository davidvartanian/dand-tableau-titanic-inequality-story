# Titanic Survival Visualisation

## Summary 
My visualisation shows that the Titanic didn't sink equally for everyone. There were clear differences by gender and social class during the rescue process, since the amount of lifeboats was lower than required.

## Design
* I decided to assign the column Survived to Rows to compare with other variables, assigned to Columns or visual encodings.
* I encoded Sex as pink/blue colours, and Pclass as blue/orange/red colours, because they are categorical values, not so many to confuse the reader.
* I used a treemap to display the cabins distribution, showing prices as a scaled colour (not used in the story).
* Used vertical bars and a calculated field using values from [this website](https://blogtanic.wordpress.com/tag/titanic-survival-rates/) to show the survival probability depending on genders by using pages filtering by Age to create an animation.

## Feedback
I used a Google Form to collect feedback from people. Here is the Google Sheet linked to the form:
https://docs.google.com/spreadsheets/d/1MwQZDQctq0VwDO_zU3CcGJtMTQoQQ-jr7TkEp19bfM4/edit?usp=sharing

### General Comments
* Impressive work, very clear to read and understand what the figures are here to say
* It would help if same attributes used the same colors/shades through different charts (i.e. men always some kind of blue etc). I didnt get why there is a slider in the last viz
* The graphs are very eye-catching, especially the one about class survival probability. The research is interesting and the data displayed nicely.
* nice, easy to understand quickly, good layout. not sure what to criticise, maybe continuity with colours (first female dark blue, then male)
* The graphic part was really appealing and it was interesting just to discover how the data was distributed, also the way of dividing the information was easy to understand.

### Improvement Suggestions
* Improve the title of Titanic Gender survival probability - maybe a sentence like the first 2 visualizations? In order to make it clearer. ie Survival Probability depending on genders
* A brief introduction at the top of the visualization, below "Titanic Rescue Inequality", could allow the reader to understand right away what the figures are about. Also, in the figures featuring "Survived - Yes/No" I would put "Survivors - Casualties" instead. Easier and clearer to understand.
* The Class Survival Graph could be less chaotic.

### Design Actions taken based on feedback
* Make sure about the use of uniform colours for the same class
* Change the title of "Titanic Gender survival probability" to  (for instance) "Survival Probability depending on genders"
* Add an explanatory introduction text below the main title
* Change aliases: "Survived - Yes/No" to "Survivors / Casualties"
* Unify casualties colour (gray) to emphasize female and male survivors

## Resources
* https://www.ryansleeper.com/practical-tableau-create-icon-based-navigation-filters/
* https://www.kaggle.com/c/titanic/data
* https://vimeo.com/129102494
* https://blogtanic.wordpress.com/tag/titanic-survival-rates/