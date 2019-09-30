![programmer joke: !false (it's funny because it's true)](https://storage.googleapis.com/replit/images/1569512326719_407dad6e2667dc94c76a8c0bcc18e25d.jpeg)

**BO0O0OLEANS**!
Here we go into our journey to make a traffic light...

* Create a variable named `iGetTheJoke` and make it equal to a boolean value;
* Create a variable called `havingFun` that holds the boolean value that corresponds to whether or not you are. In general, if not in this quiz. 
* Create a variable called `learning` that holds the boolean value that corresponds to whether or not you are. 
* Create a variable called `killingIt` and define it in terms of the previous two variables such that it is true if and only if both are. 


Now let's make some functions!

* Create a function named `returnFalse` that takes one parameter and it always returns `false` no matter what the parameter is!

```
INPUT: returnFalse(2)
OUTPUT: false
INPUT: returnFalse(hello)
OUTPUT: false
```
    
* Create a function named `theOpposite` that takes one parameter that is a boolean and it returns the opposite of it!
```
INPUT: theOpposite(true)
OUTPUT: false
INPUT: theOpposite(false)
OUTPUT: true
hint **check bang operator**
```

* Create a function named `both` that takes two parameter that are booleans and returns true if they're both `true` and `false` otherwise.
* 
```
INPUT: both(true, false)
OUTPUT: false
INPUT: both(false, true)
OUTPUT: false
INPUT: both(false, false)
OUTPUT: false
INPUT: both(true, true)
OUTPUT: true
hint **check and operator**
```

* Create a function named `either` that takes in two parameters that are booleans and returns `true` if either is `true`, and `false` otherwise.

```
INPUT: either(true, false)
OUTPUT: true
INPUT: either(false, true)
OUTPUT: true
INPUT: either(false, false)
OUTPUT: false
INPUT: either(true, true)
OUTPUT: true
```

* Create a function named `neither` that takes in two parameters that are booleans and returns `false` if they're both `false`, and otherwise returns `true`.

```
INPUT: neither(true, false)
OUTPUT: false
INPUT: neither(false, true)
OUTPUT: false
INPUT: neither(false, false)
OUTPUT: true
INPUT: neither(true, true)
OUTPUT: false
```

* Create a function named `itsComplicated` that returns `true` if the first parameter is `false` or if both the second and third are true. Otherwise it returns false.

```
INPUT: itsComplicated(false, false, false)
OUTPUT: true
INPUT: itsComplicated(true, true, true)
OUTPUT: true
INPUT: itsComplicated(true, true, false)
OUTPUT: false
```