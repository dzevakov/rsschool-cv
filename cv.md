# Dmitry Zevakov
----------------
### Contact information
- tel: **+375445141014**
- e-mail: **dmitryzev@gmail.com**
- Discord: **ZDmitry(@dzevakov)**

### About myself
My aim is to become a specialist in **Front-End Development**

##### Hardskills
- JavaScript
- HTML
- CSS
- Git

##### Softskills
1. purposefulness
2. curiosity
3. ability to quickly learn new things
4. ability to perceive a large amount of information
5. ability to independently plan my working hours and follow this plan

### Example of code
```javascript
const bubbleSort = (input) => {
  let tempNumber;
  for (let i = 0; i < input.length - 1; i++) {
    for (let j = 0; j < input.length - 1 - i; j++) {
      if (input [j] - input [j + 1] > 0) {
        tempNumber = input [j + 1];
        input [j + 1] = input [j];
        input [j] = tempNumber;
      }
    }
  }
  return input;
};
```