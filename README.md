# JavaScript-Algorithm-and-Data-Structures
Confirm the Ending
Check if a string (first argument, str) ends with the given target string (second argument, target).

This challenge can be solved with the .endsWith() method, which was introduced in ES2015. But for the purpose of this challenge, we would like you to use one of the JavaScript substring methods instead.
 The substr() method is a string method used to extract part of a string and return a new string of the extracted part.
 Takes two parameters start and length of the part to be extracted.
 substr(start, length).
 Hence the str.substr(-target.length,target.length
 This takes the str and applies the substr method to it, and extracts from the end thats why we use the negative sign.
 -target.length is meant to indicate the position to start the extraction. 
