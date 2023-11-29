# Thanh Duc Dong

## Junior Front-end Developer
***
### Personal Info

**Date of birth**
28 September 1994

**Address** 
Hannoversche Straße 1, 30001 Hannover

**Phone number**
+49 1515 468 5984

**E-mail** mishkadong@gmail.com

### Social media

* [LinkedIn](https://www.linkedin.com/in/misha-dong-0aa793248/)
* [GitHub](https://github.com/mishkadong)
* [Instagram](https://www.instagram.com/vn_michelangelo/)
* [Facebook](https://www.facebook.com/youngboizz/)

### Soft skills

* Communication skills
* Self-organisation skills
* Creative skills
* Fast learner
* Logics and critical thinking

### Hard skills

* HTML5
* CSS/SASS
* JS
* React

### Code Example
**Task:**

Given:
```
hero = ['Ivan'];
native = ['York','Of'];
destination = ['Poltava','In'];
```
Using loops, if/else, switch/case and methods .push(), .pop(), .unshift(), .shift(), .concat(), .splice(), .reverse() .join() :

1. Combine the *destination*, *native*, *hero* arrays into a common rainbow array.

2. Reverse the elements of the resulting rainbow array.

3. Change/add elements of the rainbow array so that you end up with an array like 

`['Richard','Of','York','Gave','Battle','In','Vain'];`

4. Print the elements of the resulting array to the console as a string.

**Solution:**
```
let hero = ["Ivan"];
let native = ["York", "Of"];
let destination = ["Poltava", "In"];
let nameToDestination = [];
hero = hero.join("").toLowerCase().split("");
nameToDestination.push(
  hero.find((i) => i == "v").toUpperCase(),
  hero.find((i) => i == "a"),
  hero.find((i) => i == "i"),
  hero.find((i) => i == "n")
);
hero = nameToDestination.join("").split();
let rainbow = [...destination, ...native, ...hero].reverse();
rainbow.pop();
let place = [rainbow.pop(), rainbow.shift()];
rainbow.unshift("Richard");
rainbow.push("Gave", "Battle");
console.log(rainbow.concat(place).join(" "));
```

### Education

**2000 - 2011**:       Kharkiv high school

**02.2022 - 05.2022**: online course "Front-end Basic" in Hillel IT school

**08.2022 - 12.2022**: online course "Front-end Pro" in Hillel IT school

### Certificates
**05.2022**:           graduated "Front-end Basic" course
**12.2022**:           graduated "Front-end Pro" course

### Languages

* **ukrainian** native speaker
* **russian** native speaker
* **english** A2-B1
* **german** B2