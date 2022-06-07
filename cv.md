https://Fadin-47.github.io/rsschool-cv/cv

## Fadin Alexey

### Junior Frontend Developer
___
#### Contact information:

**Phone:** +7937 999 99 99\
**E-mail:** RsShool@gmail.com\
**Telegram:** aafadin47\
[Vk](https://vk.com/#)
___

#### Briefly About Myself:
Received the profession of an energy engineer. But today I understand that this is what I would like to do all my life.
He left to work in the technical support of computers, hoping to master the development. Today we are working and creating a new product to automate the work of other support engineers.

I’m interested in Web Development because this occupation provides endless possibilities for professional growth,
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.
___

#### Skills and Proficiency:
* HTML5, CSS3
* JavaScript
* Git, GitHub
* React
* Node.js
* SQL
---

#### Code example:
**Peak array index KATA from CODEWARS:** Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.

`function peak(arr) {

for (let i = 1; i < arr.length - 1; i++) {
let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
if (leftSum === rightSum) {
return i;
}
}
return -1;
}`