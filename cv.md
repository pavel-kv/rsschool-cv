# PAVEL KARPENKO

### Junior Frontend Developer


## Contact information
* __Minsk__
* __Email:__ pawel.kv@gmail.com
* [__CodePen__](https://codepen.io/paww118822)
* [__Linkedin__](https://www.linkedin.com/in/pavel-karpenko-74a79625a)


## About
I am a thoughtful, accountable and self-motivated specialist excited about web development.
I improve my knowledge about web development and apply my skills into practice.
Thirst for new knowledge, perseverance and passion are the qualities that allow me to achieve high results and enjoy web development.


## Skills
* HTML, CSS, BEM methodology
* JavaScript: Fundamentals, Functional Programming, OOP, ES6+, DOM, JSON
* Project builders: WebPack
* Package manager: NPM
* Version control: git, GitHub
* IDE: Visual Studio Code
* Databases: basic understanding of SQL, Firebase
* Graphics editors: Adobe Photoshop
* English level: B1 (freely read technical documentation)


## Code example
__Exes and Ohs from CODEWARS:__ Check to see if a string has the same amount of 'x's and 'o's. The method must return a boolean and be case insensitive. The string can contain any char.

```javascript
function XO(str) {
  let result = str.toLowerCase().split('').reduce((sum, item) => item == 'x' ? ++sum : item == 'o' ? --sum : sum, 0);
  return !result ? true : false;
}
```