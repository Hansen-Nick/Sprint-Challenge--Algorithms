#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n). The n^3 is offset by the n^2 increase in a within the loop. Operations will increase by a set amount per increase in n

b) O(nlogn) This is because the outer loop is O(n) and the inner loop is log(n)

c) O(n). This is due to the increase in a bunny creating one more recursive statement

## Exercise II

Start in the middle of list of floors(n) in order

if array is only 1 item:
return remaining item(floor)

Begin in the middle, and drop an egg.
if it breaks, look to left (below) of the floor
run it again (resurive) but only with floors to the left

    if it does not break, look to right (above) of the floor
        run it again(recursive) but only with floors to the right

runtime complexity if O(logn)
