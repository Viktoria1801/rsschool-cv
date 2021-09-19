# Lazko Viktoria

## My contact info
* __phone:__ +375445600250
* __E-mail:__ lazkovika1@gmail.com  
* __GitHub:__ [Viktoria1801](https://github.com/Viktoria1801)

## About me
My goal is to become a full-stack developer who would be able to implement himself in as many areas of programming as possible. My strengths are to constantly learn something new, to achieve better and better results and, of course, in hard work, perseverance and purposefulness.

## Skills
_Begginer:_
* Java
* JavaScript
* Python
* C, C++

## Code example
__Task from CODEWARS:__ Array.prototype.length will give you the number of top-level elements in an array.
Your task is to create a function deepCount that returns the number of ALL elements within an array, including any within inner-level arrays.
```javascript
function deepCount(a){
  let count = 0
  count += a.length
    
  while (a.length > 0) {
    let array = a.shift()
    if ((typeof array).includes('object')) {
      count += deepCount(array)
    } 
  }
    
  return count
}
```

## Courses
1. Introduction to Data Science in Python (28.07.2020)
2. Using Python to Access Web Data (03.10.2020)
3. Neural Networks and Deep Learning (27.10.2020)
4. Convolutional Neural Networks (29.01.2021)  
[coursera](https://www.coursera.org)

## English
__A1__  
Courses:
* Grammer and Punctuation (01.11.2020) [coursera](https://www.coursera.org)
