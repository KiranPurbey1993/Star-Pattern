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
##### 2. Hollow  Square Pattern
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
##### 3.  Left Triangle Pattern in Javascript
```
let n = 5;
let string = "";
for (let i = 0; i <= n; i++) {
 
  // printing star
  for (let k = 0; k < i; k++) {
    string += "*";
  }
  string += "\n";
}
console.log(string);
*
**
***
****
*****
```

###### 4. Downward Triangle Star Pattern
```
let n = 5;
let string = "";
for (let i = 0; i <= n; i++) {
 
  // printing star
  for (let k = n; k > i; k--) {
    string += "*";
  }
  string += "\n";
}
console.log(string);
*****
****
***
**
*
```

###### 5.hollow triangle star pattern
```
let n = 5;
let string = "";
for (let i = 0; i <= n; i++) {
 
  // printing star
  for (let k = 0; k < i; k++) {
      if(i===n){
         string += "*"; 
      }else{
          if(k===0 || k===i-1){
             string += "*"; 
          }else{
            string += " ";   
          }
          
      }
    
  }
  string += "\n";
}
console.log(string);
*
**
* *
*  *
*****
```



