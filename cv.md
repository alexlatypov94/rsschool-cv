# Aliaksei Latypau

  Student
  
## Contact

  * e-mail: alex.latypov94@gmail.com;
  * phone: +375(29)266-47-20
  * Telegram: @alexlatypov
  
## Summary

  *I want to become a front-end develover. 
  I graduated from the Belorussian-Russian university in 2017 and received master's degree in 2018. 
  Currently working as a process engineer
  My strengths are stress resistance, the desire to learn something new, I learn quickly and am attentive to the little things in my work.*
  
## Skills 

  * HTML
  * CSS
  * JS
  
## Code example
```
        function transform(arr) {
        if (!Array.isArray(arr)) {
          throw new Error();
      }
        let newArr = [];
        for (let i = 0; i < arr.length; i++) {
         if(arr[i] === '--discard-next') {
           if (arr.length - i >= 2) {
            i++
           }
         } else if(arr[i] === '--discard-prev') {
            if (i >= 1 && arr[i - 2] !== "--discard-next") {
              newArr.pop()
            }
         }else if(arr[i] === "--double-next") {
           if(arr.length - i >= 2) {
             newArr.push(arr[i+1])
           }
         }else if(arr[i] === "--double-prev") {
           if(i >= 1 && arr[i-2] !== "--discard-next") {
             newArr.push(arr[i-1])
           }
         } else {
          newArr.push(arr[i])
        }
        }
        return newArr
      };

```
## Education

  * *Belorussian-Russian university (2017 specialist)*
  * *Belorussian-Russian university (2018 magistracy)*
  * *courses of basic objective-oriented programming*
  
## English

  English (А1+) (A2)
