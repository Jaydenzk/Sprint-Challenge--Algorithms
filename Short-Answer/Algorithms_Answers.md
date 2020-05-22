#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)Assume that n=len(something), then the running time should be O(n). The while loop looks to be n^3 and inner loop is increasing a by n^2 with each iteration. So, the equation should be n^3/n^2 = n thus runtime should be O(n)


b)The for loop runs in range of n times, and the inner while loop has j which it doubling with each iteration that this is log(n). The total runtime for this example is O(n log(n)).


c)BunnyEars seems called recursively once for every bunny. so runtime should be O(n)

## Exercise II

I would use binary search approach on this question

let's start on the middle floor and drop the egg the middle floor should equal to total number of floors/2

2 assumption can be shown here

If egg Not break then move halfway up to the top floor

If egg break move halfway down to the bottom floor

Repeat this process in a loop until the floor has lowest number of broken eggs

The runtime of this method should be O(n log n) since

