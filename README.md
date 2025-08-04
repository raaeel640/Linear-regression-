## Linear-regression
It is important as it is easy to use and foundation for other algorithms
It is a supervised ML algorithm that predicts the values based on previous data, in order to minimize the errors between original and predicted values it jut draw a traight line that fit
between the points.
It is further divided into types i.e:
Simpl(1 input and 1 output column)
Multiple(more than 1 input and output columns)
Polynomial LR(when data is not linear)
Data may not be completely linear becasue the data is real world and maybe effected by real world factors(called as stochastic errors:they actually make data look some sort of linear)
We can draw a best fit line that passes very closely to all points giving zero errors ,We train the model in such a way that 
if we provide it with any value of CGPA it will calculate the package of that very GPA by using the equation y=mx + c  making c =0 ,
doesn’t affect value of y ,but if mx becomes zero(not in this case of CGPA but if we talk about a fresher with 0 experience then this value becomes 0 then y totally 
depends on c then our value of y will depend on c )

We have to find m and c for that we have 2 solutions
1)	Closed form solutions (called as OLS finding out the value of a variable by substituting values of other variables) i.e direct formula 
2)	Non closed form solutions(using approximation techniques)

For higher level when data increases we use Gradient descent 
Value of b through OLS 
## b=y’-mx’
##  m= ∑(xi-x’)(yi-y’)/ ∑ (xi-x’)^2
 
if we draw a best fit line there are n number of points to find distance between them formula is E=d^2=d2^2+d3^2+….dn^2 = ∑ di^2 this is an error function 
finding m and c which minimizes the value of error function 

