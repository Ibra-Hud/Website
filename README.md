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

To get the current time in military format we can use this code below...
One major diffrence bertween "==" vs "===" is that "==" is "not strictly" while "===" is strictly meaning, the code below evaluates to True.

```js
const printTime = () => {
    const time = new Date();
    let hours = time.getHours()
    let minutes = time.getMinutes()
    let seconds = time.getSeconds()

    console.log(`${hours}:${minutes}:${seconds}`)
}

printTime()
```
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

Best practice to merge a branch into the main 
```sh
git checkout main # switch to the main branch
git merge <branch_name> # merge a branch into the current branch
```

Best way to create a branch and switch to it
```sh
git checkout -b <branch_name>
```

Best practice to merge a branch into the main 
```sh
git checkout main # switch to the main branch
git merge <branch_name> # merge a branch into the current branch
```