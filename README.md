# Discrete maps plotted in python and Julia. 

## Here, the y-axis represents the x_n after Nth iterations. While, x-axis represents the parameter r. 

# Logistic map

## x(n+1) = rx(n)(1-x(n))

Set number of points in r to 10000 and points in X to 400 to generate this graph (for python, took around ~10 mins (on i5 8265u) to give the following graph)

![img_4](https://user-images.githubusercontent.com/55867762/195908517-3e651ad6-9e89-453b-8113-26337c2434c4.png)

The above is obtained by Julia plots. The "Plots" package is still very buggy for Julia. Future improvements to make this faster will be coming soon! 

![plot2](https://user-images.githubusercontent.com/55867762/196008026-a54eca31-f549-4f03-b2d8-bd765db54617.png)

# Tent map

## x(n+1) = r(1 - |1-x(n)|)


Tent map in Julia. Took around ~3-4 min (on i5 8265u) for this graph to plot

![plot_tent_map2](https://user-images.githubusercontent.com/55867762/196038527-6f4c4cd7-a555-4fd7-b415-de596753c306.png)
