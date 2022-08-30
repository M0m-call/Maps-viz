# Maps-viz

This piece of code allows you to visualize your functions from R ro R 
Or from C to C

![fun](https://user-images.githubusercontent.com/63225559/187446867-94a383ec-5d6d-4998-a5ec-dba27979259a.png)


This code is born out of the following intution that I wanted to verify regarding holomrphic functions.

warning :Math stuff ahead !

" Take an open ball of radii r around a point p  in the complex plane , 
Now look at the image of that ball  under our holomorphic  function say f,
Then as r tends to 0, the ratio of the diam of ouu ball and it's image should tend to | f'(p) | 
magnitude of the derivative at that point p "

I wanted to do the same thing for Real valued function and hence the r to r file.



What have I done here is as follows:

I'm taking a mesh grid of numpy array 
than plotting it as a polar graph via matplotlib

than I'm applying our desired function to that array
and again plotting it in complex plane/Real line.



