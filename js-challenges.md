# JavaScript challenges

## Print an staircase

Given next function call: 

`staircase(8);`

Must print next output:

````
        #
       ##
      ###
     ####
    #####
   ######
  #######
 ########
````

Solution:

```javascript
function staircase(steps) {
  for (let i=1; i <= steps; i++) {
    console.log(" ".repeat(steps-i), "#".repeat(i));
  }
}
```



