# Finite Difference Exercise

In this exercise, we will approximate derivatives with Python. In order to do this, we need to recall the formula for the derivative from first principles, which is the definition of the derivative.

![Derivative First Prin](first_diff.png)

While it isn't easy to simplify algebraic expressions involving limits using Python, we could obtain an estimate for the value of the derivative by calculating the expression on the right hand side for small values of h. 

Let's code this formula into a function which takes as its inputs:
* f - the function whose derivative we wish to approximate
* x - the value at which we wish to approximate the derivative
* h - the value of the difference in the formula

and outputs an approximation for the derivative using the formula:

![Derivative First Diff](first_diff2.png)

{% next %}

Now let's use our previous work to approximate the derviative of: 
![Function](function.png)

at x = 5 using h = 0.01.

{% next %}

Lastly, we will plot the function and it's derivative on the interval \[-4, 4].

{% spoiler %}
The interval \[-4, 4] is the same thing as saying -4 <= x <= 4. 
{% endspoiler %}
