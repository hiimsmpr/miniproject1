# Loops & Conditionals!

![ouroboros](https://media.giphy.com/media/l3q2y10JYA3ZSNGus/source.gif)

We have some problems for you to solve! Write your answers in the appropriate sections of `answers.js`.


#### Easy Going
* Write a for loop that will log the numbers 1 through 20.

&#x1F534; The commit message should read: <br>
"Easy Going answered"

#### Get Even
* Write a for loop that will log only the even numbers in 0 through 200.
>Hint: Think about the increment expression.

&#x1F534; The commit message should read: <br>
"Get Even answered"

#### Fizz Buzz

This is a classic problem that you should get really comfortable solving. If you've solved it before, try to make it more elegant and short.

1. Write a javascript application that logs all numbers from 1 - 100.

2. If a number is divisible by 3 log "Fizz" instead of the number.

3. If a number is divisible by 5 log "Buzz" instead of the number.

4. If a number is divisible by 3 and 5 log "FizzBuzz" instead of the number.

&#x1F534; The commit message should read: <br>
"Fizz Buzz answered"

#### Wild Wild Life
Use the following arrays to answer the questions below (name,species ,age, hometown):
You should be modifying the elements by accessing them. It is up to you which methods to use.

```js
const wolfy = ["Wolfy", "wolf", 16, "Yukon Territory"]
const sharky = ["Sharky", "shark", 20, "Left Coast"]
const plantee = ["Plantee", "plant",  5000 , "Mordor"]
const porgee = ["Porgee", "Porg", 186, "Ahch-To"]
const dart = ["D'Art" , "Demogorgan Dog", 2, "Upside Down"]
```
1. Plantee just had her birthday; change Plantee's array to reflect her being a year older.

2. Change Wolfy's hometown from "Yukon Territory" to "Gotham City".

3. Give D'Art a second hometown by adding "Hawkins"

4. Porgee decides that Wolfy can't be named "Wolfy" anymore. Remove "Wolfy" from the `wolfy` array and replace it with "Gameboy".

&#x1F534; The commit message should read: <br>
"Wild Wild Life answered"

#### Methods, Revisited

Here is a list of favMovies:

```
const favMovies = ['Jaws', 'The Fellowship of the Ring', 'Howl\'s Moving Castle', 'Django Unchained', 'Cloud Atlas', 'The Usual Suspects', 'Toy Story', 'Conan the Barbarian', 'Titanic', 'Harry Potter', 'Fried Green Tomatoes', 'Volver', 'Oculus', 'Seven', 'Black Panther', 'Harry Potter', 'Imitation of Life', 'Snatch', 'Fast and Furious'];
```

- Console log:  the index of `Titanic`

- Do the following and console.log the final results (I have included some *thought* questions, you don't have to write out an answer for those marked as such):

Note: if you have to add to the array, feel free to add any movie you'd like

 1. use the `.sort` method Thought question: what did this do to the array? Did it permanently alter it?
 1. Use the method `pop`
 1. `push` "Guardians of the Galaxy"
 1. Reverse the array
 1. Use the `shift` method
 1. `unshift` - what does it return?
 1. `splice` "Django Unchained" and add "Avatar" (try finding the index of "Django Unchained", instead of counting it yourself) Thought question: did this permanently alter our array?
 1. `slice` the last half of the array (challenge yourself and try to programatically determine the middle of the array  rather than counting it and hard coding it) - Thought question: did this permanently alter our array?
 1. store the value of your `slice` in a variable, console.log it - Thought question: what is going on here?
 1. console.log your final results

- After running the above tasks, console.log the index of "Fast and Furious"
    -We removed it from the array, what value do we get when we look for the index of something that is not in the array?


&#x1F534; The commit message should read: <br>
"Methods Revisited answered"
