# k-armed bandit problem 
is when you are given k decisions coming as sequence to choose and get the reward from them. you have to maximize your reward

![](2023-03-26-22-11-26.png)

# action-values

### sample-average method
take average of result set to consider which decision is better

![](2023-03-26-22-13-02.png)

then you can choose the highest average

![](2023-03-26-22-13-28.png)


# action-values incrementally

the idea of this evaluating is get contributions from all the previous estimated rewards

![](2023-03-26-22-20-59.png)

full formula:

![](2023-03-26-22-21-50.png)

