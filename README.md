# Codewar-4
Problem: It's pretty straightforward. Your goal is to create a function that removes the first and last characters of a string. You're given one parameter, the original string. You don't have to worry with strings with less than two characters.

Solution:
function removeChar(str){
var first = str.slice(1,str.length-1)
return first;
};

Explained:
So what I did for this problem is i made a function that to our parameter str . Then I made a variable named first and assined it str.slice(1, str.length-1), .slice is a javascript method that will slice the string the way we want to. I slice the string at index element 1 and and the last element. Then I return whats left which is the middle of my string. For example is I used string "cat" as my parameter this function would return my string without the first or last character resulting in an output of "a".
