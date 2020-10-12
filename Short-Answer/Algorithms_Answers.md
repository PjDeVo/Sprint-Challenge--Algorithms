#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) this is an O(n) time complexity because the number of times the loop will run depends solely on what the value n is passed in.


b) O(n^2) two loops both O(n) but the second loop is nested making it O(n^2)


c) This could be a constant O(1) if bunnies is = 0 or linear in which case it would be O(n) due to recursion that depends on what the bunnies passed in is which makes it linear

## Exercise II

<!-- Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution. -->

n is the number of floors

f is the value of max floor allowed before egg breaks

we could do this linearly which would be throwing the egg from the bottom floor
and going to the top until the egg breaks but that would pose a problem if the
egg breaks at the max floor and wouldn't be super effective 
but would be a naive solution.

but if we want to find f quickly we could do a binary type method

max floor //2 if the egg breaks do max//2's value and //2 again until we find a floor where it doesn't break then go up from there until it breaks

this would be O(logn)

