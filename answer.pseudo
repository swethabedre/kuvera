/**
 * @desc Generates a random integer between 6 and 16 using Math.random()
 * @param string name - Represents a noun
 * @return string - Name and GeneratedNumber eg. "Swetha 10"
 */

function RandomNumber(name) {
    //minimum random number to be generated
    var min = 6;
    //maximum random number to be generated      
    var max = 16;
    /** Calculate a random number.
     *  Math.random() returns a random floating point number between 0 and 1.
     *  Multiply the random floating number to the difference of max and min.
     *  This will give you floating number, which is less than the difference of max and min. eg. from 0 to 9
     *  Use Math.floor to get largest integer, which is less than or equal to 9.
     *  We need to add mininum number, to the integer number, so that the randrom number is not from 0 to 10, but from 6 to 16
     */
    var generatedNumber = Math.floor(Math.random() * (max - min)) + min;
    return name + " " + generatedNumber;
}

var result = RandomNumber("Swetha");
console.log(result);