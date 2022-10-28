# Star-Pattern

##### 1. Square Pattern
```
var string = "";
for(var i=0;i< 5;i++){
    for(var j=0;j<5;j++){        
        string += "*";
    }    
    string += "\n";
}
console.log(string);  
*****
*****
*****
*****
*****
```
##### 1. Hollow  Square Pattern
```
let n = 5; // row or column count
// defining an empty string
let string = "";

for(let i = 0; i < n; i++) { // external loop
  for(let j = 0; j < n; j++) { // internal loop
    //
    if(i===0 || i === n-1){
         string += "*";
    }else{
        if(j===0 || j === n-1){
         string += "*";
        } else{
          string += " "; 
        } 
    }
  }
  // newline after each row
  string += "\n";
}
// printing the string
console.log(string);
*****
*   *
*   *
*   *
*****
````
