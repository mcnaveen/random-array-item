# Random Array Item

![Build](https://github.com/mcnaveen/random-array-item/workflows/Build/badge.svg)
![Downloads this Week](https://img.shields.io/npm/dw/random-array-item)
![Bundle Size](https://img.shields.io/bundlephobia/min/random-array-item)
![Version](https://img.shields.io/npm/v/random-array-item)

![Numify](./images/cover.png)

:unicorn: Simple utility to fetch a random item from an array.

### :package: Requirements

Node.js 12.x LTS or 14.x (or Higher) LTS

### :sparkles: Installation

Install the NPM Package with the below command:

```
npm install random-array-item --save
```

(or)

Install with Yarn:

```
yarn add random-array-item
```

### :pen: Usage

Import the module in your project:

```javascript
// Commonjs Import
var { randomArrayItem } = require("random-array-item");

// or ES6 import
import { randomArrayItem } from "random-array-item";
```

### :bulb: Example

Pass the Array to the function

```javascript
import { randomArrayItem } from "random-array-item";

let array = ["1", "2", "3", "4", "5", "6", "7", "8", "9", "10"];
let randomItem = randomArrayItem(array);
console.log(randomItem);
```

### :ballot_box_with_check: Example Output

```
7
```

### :shield: LICENSE

- MIT

---

#### :green_heart: Message

I hope you find this useful. If you have any questions, please create an issue.

---

#### 💰 Help me with your donation

<a href="https://www.buymeacoffee.com/mcnaveen" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
