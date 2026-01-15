Inital Plan
    - My inital plan is to walk through the html and change outstanding problems/issues
    - The next script to chack is the CSS Code and chage issues and list thoes changes and tinker with values for the site
    - after css I plan on adding the js which I'll make comments for anything outstanding/aproached differently

HTML Inital error catches
    Initally Removed Code
    - Line 5, column 3; to line 5, column 26
        <meta charset="UTF-8" /> is not needed
    - Line 6, column 3; to line 6, column 74
        <meta name="viewport" content="width=device-width, initial-scale=1.0" /> is not needed
    - line 112, column 13; to line 112, column 33
        <img src="" alt="" /> Removed because src cannot be an empty value

Changed Code

CSS Errors
    - line 52
    Changed box-shadow: 1 2px 4px rgba(1, 1, 1, 0.3); to box-shadow: 1px 2px 4px rgba(1, 1, 1, 0.3);
    - line 97
    Changed box-shadow: -1 1px 3px rgba(1, 1, 1, 0.2); to box-shadow: 1px 1px 3px rgba(1, 1, 1, 0.2);
    - line 106
    Changed from -1 to 1
    - line 118
    Not allowed negative values (- was removed)
    - line 123
    Not allowed negative values (- was removed)
    - line 156
    Not allowed negative values (- was removed)
    - line 168
    Not allowed negative values (- was removed)

Css Warnings and Fixes
    - line 98
    Negitive value -2 with be interpeted as 0 so I changed the value to 1

JS Code
    NOTE: Step 5 doesn't show any text in the site because the characters array has no error. However I noticed an error from the inital file by adding the ',' in line 5 back and fixed it. I also texted step 5 by removing the name from a few characters from the chracters array. 

    - For step 5 I made it so the function has two prams where its the array and the div element with id that we want to assign it to

    What is required for the output
    1. The characters array with names so we can make a list of the characters name
    2. Age in the characters array so we can use character.filter to check for each objects age under 40
    3. Same thing as step 1 but in a reuseable function so it can be called in diffrent places in the script
    4. Similar to step 2 but we make it so the age doesnt have to be 40 and can be any age of our chosing
    5. The goal for step 5 is to error handle and check if the names in the given array are missing or not and to log and show the error
    6. Creating a new array for testing purposes and to alter step 5 so we can add any element id we want with the array to customize what is shown