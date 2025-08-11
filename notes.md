# AI Prompt to start the project
Create a Pain Tracking html page. Which has the following components : 
The application is in French

Add button, which displays the following form/template and its options

Form/template : 
Date: Current date stamp
Time : Current time.
Pain Change Type column with 3 radio buttons. 
- Increase
- Decrease
- No change
Activity before pain spike:: Checkbox with the following default  
 - Adducteur
 - Psoas
 - Hanche
 - Descendre le adducteur
 - 
 - Gentle walk
 - Sat in cafe
 - 5 mins pause & stretch 
 - Assis au bureau a la maison. Assis dans la chaise du jardin
 - Gym rameur 10 mins
 - Gym upper body workout
 - Allongé au lit
 - Assis dans la chaise du jardin.
 - Other: Free text field
Movement / Exercise: Checkbox with the following default options  for easier data entry 
 - Glute bridge
 - Cycling
 - Stretching
 - Other: Free text field
Movement type: Checkbox with the following default options for easier data entry 
 - Static
 - Repetitive
 - Stretching
 - Exercise
 - Other: Free text field
Pain level: Radio buttons with the following options
- 0 
- 1
- 2
- 3
- 4
Change: Radio buttons with the following options
- Up
- Down
- Same
Relief method: Checkbox with the following default options for easier data entry 
- Change of environment
- Stretching
- Sitting  
- Walking
- Lying

Notes (stress, sleep, fatigue, cold, weather):
Possible trigger : Checkbox with the following default options for easier data entry
- Activity after period inactive.
- Sitting too long 
- Other: Free text field
Below is a submit button which add the form data into a table below the form. Each new form submission creates a new row in the table. 

Below the table is an export data button. 
Saves your pain entries in localStorage as JSON
The table data is exported in CSV format 
The data is stored locally on my iphone
Add a version number to the end of the The exported files