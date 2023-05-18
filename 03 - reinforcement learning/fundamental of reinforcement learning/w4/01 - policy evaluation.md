we can actually "Learn" a value function

# iterative policy evaluation
compute new values based on current values -> update new values -> repeat until no improvement

we can update our current value based on our native recursive equation

![](2023-05-04-22-11-47.png)

### compute new values

calculate new value for every states based on last values

![](2023-05-04-22-12-51.png)

### update old values

then update all new values to old values

![](2023-05-04-22-13-30.png)


# Example

![](2023-05-04-22-14-03.png)

step 1: init values

![](2023-05-04-22-14-28.png)

step 2: compute new value based on new states' values

![](2023-05-04-22-15-33.png)

![](2023-05-04-22-15-49.png)

step 3: update old values

![](2023-05-04-22-16-10.png)

# Pseudo code

![](2023-05-04-22-16-25.png)