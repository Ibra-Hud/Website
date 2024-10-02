# Tips, Syntax, and Quick Fixes
**Sections**
* Html
* CSS
* JavaScript
* Git


## Html
```html
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## JavaScript
One major diffrence bertween "==" vs "===" is that "==" is "not strictly" while "===" is strictly meaning, the code below evaluates to True.

```js
let check = (num1, num2) => {
    if (num1 === num2){
        console.log("Correct")
    }
}

check(1, "1")
```
but if we used "===" it would evaluate to false.


## Git
Basic Git Order
```sh
git init
git status
git add
git commit 
git clone
git push
```

Best way to create a branch and switch to it
```sh
git checkout -b <branch_name>
```
