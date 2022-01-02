# Oksana Lifanenkova #

## Contacts ##
* LinkedIn: [Oksana Lifanenkova](http://www.linkedin.com/in/oksana-lifanenkova-238256185)
* GitHub:   https://github.com/Lifanenkova
* E-mail:   olifa19@gmail.com
* Discord   Oksana#0227

## About me ##
I want to work and study new technologies.
I know, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

## Skills ##
* HTML5
* CSS3 (SCSS)
* JavaScript
* Git

## Code example ##
```
function flat(arr1, dep){
    const newArr = [];
    flatRec(arr1, dep);

    function flatRec(arr, dep){
             arr.forEach(element => {
            if(Array.isArray(element)){
                if(dep === 0){
                    newArr.push(element);  
                     return newArr;
                }
                dep--;
                flatRec(element, dep);
            }else{
            newArr.push(element);  
            }
        }); 
    }
    return newArr;
}
```

## Experience ##

