# Process Writeup

## Name: Josiah Benitez
## Course: Unit 10
## Period: 7
## Concept: Recursion

### Overview
Unit 10 was very difficult for me to first grasp and it honestly was probably the hardest Unit for me overall as it was hard to grasp.

## First Challenge
### A slip in my judgement

In question 11 its asking "Which of the following should be used to replace // Missing line in hasRepeatHelper so that hasRepeat will work as intended?". I messed up and I envisioned a regular list in my head going from 1-10 in order. This caused me to pick something that would work for that set of data which is this answer:
```java
if (pos < 2)
{
  return false;
}
```

This code wont work because it ignores if the first 2 numbers in the list are the same and that wouldnt be an issue with the list of data that I envisioned but it is a flaw in the code, which makes it a wrong answer. The correct answer was the following:


```java
if (pos <= 0)
{
  return false;
}
```

This answer goes through from the beginning not skipping anything and will be able to check if there is something that repeats or not when it is ran making it the only correct answer in this answer set.


## Second Challenge
### (Parenthesis Problem)

This next question is up there with my most silly mistakes to be totally honest. The question asks for the following: "Which of the following calls should replace /* missing expression */ in the return statement for mergeSort so that the method works as intended?" The answer I picked was this one:

```java
upperHalf[i] = arr[(i + arr.length) / 2];
```

This answer was totally correct except for 2 very little things that mean so much. There were parenthesis around `i + arr.length` and this caused it not to be the correct answer because the method wouldnt work as supposed to. The correct answer was the following:

```java
upperHalf[i] = arr[i + arr.length / 2];
```

This is the same exact thing but it doesnt have the parenthesis around `i + arr.length` making it the correct answer that I would have got if I didnt get too confident and rush.
### Takeaways

* Dont get too confident and hasty on the questions you think you know for sure because it can cause you to miss out on points.
* Take extra time to review the basics of what Unit you are on.
* Put more time towards questions that require more reading of code so you are less likely to skim over important code and end up losing a chance on points you could have got.
* Parentheses can mean the difference between a correct answer and something that doesnt work at all so be careful when reading code with important parentheses.
  
  
