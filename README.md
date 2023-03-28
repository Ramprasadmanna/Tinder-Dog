# Tinder-Dog
Html Css Bootstrap Project

q
x=c(1,2,3,4,5)
y=c(35,100,200,350,540)
plot(x,y,main="Scatter Plot", xlab="x",ylab="y")
 
r1=lm(y~poly(x,2,raw= TRUE))
r1
par(new=TRUE)
plot(x,r1$fitted.values,type="l")

ex
x=c(1,3,5,7)
y=c(5,20,100,400)
plot(x,y)
r1=lm(log(y)~x)
r1
a=exp(r1$coefficients[1])
b=exp(r1$coefficients[2])
print(a)
print(b)
fit=a*b^x
par(new=TRUE)
plot(x,fit,type="l")

import numpy as np
 
A = np.array([[1, 2], [3, 4]])
B = np.array([[1, 2], [3, 4]])
 
print(np.add(A,B))
print('\n')
print(np.multiply(A,B))
print('\n')
print(np.linalg.inv(A))
print('\n')
print(np.transpose(B))
