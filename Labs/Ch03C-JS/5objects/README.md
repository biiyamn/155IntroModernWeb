# Chapter 3C: Object practice

## Steps
 

1. Continue with your practice page. 

1. In a file called myHobbies.js - create an array of 3 of your hobbies. Each hobby should be represented as an object with a name, and lengthInYearsAtHobby. Similar to the following sports array, only with lengthInYearsAtHobby as a numeric value.

    ``` javascript
    const sportsArray = [
        { name: 'volleyball', duration: 'matches' },
        { name: 'baseball', duration: 'innings'},
        { name: 'hockey', duration: 'periods'}
    ];
    ```            

1. Create a function that takes in one hobby and prints it to console.log. Use ES6 backticks. Check out how cool backticks are!  you can concatenate without the plus symbol.  It uses ${ }  with the variable name inside.
Your work will be similar to this example
    ``` javascript
    function printSportInfo(sport) {
        console.log(` ${sport.name} is played in ${sport.duration} `)
    }
    ```

1. Now loop through your array items and call your function for each item.     ``` javascript
        printSportInfo(sportsArray[someCounter]);
    ```

1. Run from the command line using `node myHobbies`

