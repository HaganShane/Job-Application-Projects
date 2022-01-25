// Author: Shane Hagan
// Date: 1/24/2022
// Coderbyte test with javascript for application

function SimplePassword(str) { 

  // Check for a capital letter in the string. A to Z capitalized
  let CaptialLetter = /[A-Z]/.test(str);

  // Check for a number in the string. 0 to 9.
  let NumberCheck = /[0-9]/.test(str);

  // Check for one of these punctuation or math symbols in the string.
  let PuncuationCheck = /[.!?:;'',=+-]/.test(str);

  // Check for the word password in the string. /i operator deals with case sensitivity
  let PasswordCheck = (/password/i).test(str);

  // Store the string length, which we can use in the blow if operator
  StringLength = str.length;
  
  // Combine all of the above conditions. If ALL are met, we can return true, otherwise use else to return false
  if ((StringLength > 7) && (StringLength < 31) && (CaptialLetter) && (NumberCheck) && (PuncuationCheck) && !(PasswordCheck)){
    return 'true';
  }

  // If one of conditions above are not met, return false
  else{
    return 'false';
  }

}
   
// keep this function call here 
console.log(SimplePassword(readline()));

// Code is working and ran the test case successfully. Also tried apple!M7, Testing123, T3sting!. Seems to be
// fully functional and working as intended.
