# eucalypsih_rsrapsjs
[JavaScript Array reduce() - Flexiple](https://flexiple.com/javascript/javascript-array-reduce)

```javascript
cons person = {
    isHuman: false,
    printIntroduction: function () {
        console.log(`My name is ${this.name}. Am I human ${this.isHuman}`);
    },
};

cons me = Object.create(person);

me.isHuman = true;
me.name = 'moe';
me.printIntroduction();

```
