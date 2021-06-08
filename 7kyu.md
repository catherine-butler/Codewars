**I'm everywhere!**
I worked this solution out with my code pair Sellani. 

Initial solution

function i(word) {
  let vowels = /[aeiouAEIOU]/gi;
  let upperCase = /[A-Z]/gi;
  let lowerCase = /[a-z]/gi;

  if (word.charAt(0)== "I" || "i"){
    return "Invalid word"; 
  } else if (vowels > word.length){
    return "Invalid word"; 
  } else if (word.charAt(0) == lowerCase) {
    return "Invalid word";  
  } else {
  return "i" + word 
  }
}

Threw error message: expected 'Invalid word' to equal 'iPhone'