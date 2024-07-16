>[!problem]
>A biotechnology manufacturing firm can produce diagnostic testing kits at a cost if \$20. Each kit for which there is a demandin the week ofproduction can be sold for \$100. However, the half-life of components requires the kti to be scrapped if not used within a week. The cost of scrapping a kit is $5. The weekly demand can be summarized as follows:
> 1. 0(units demanded) - 0.05 (probability)
> 
> 2. 50 - 0.4
> 
> 3. 100 - 0.3
> 
> 4. 200 - 0.25
> 
>   
> 
> How many kits should be sold to maximise the mean earnings of the company?

Let x be the number of units created in a certain week

we need to maximize the earnings, thus, we can plot their **mean earnings** for a certain number of kits produced

mean Profits if 200>x>=100:
$$
0.25(x*80)+0.3(100*80-25*(x-100))+0.4(50*80-25(x-50))+0.05(-25*x)
$$
mean Profits if 100>x>=50:
$$
0.25(x*80)+0.3(100*80)+0.4(50*80-25(x-50))+0.05(-25*x)
$$
mean Profits if 50>x>=0:
$$
0.25(x*80)+0.3(100*80)+0.4(50*80)+0.05(-25*x)
$$

This is a classic case of linear programming:
![[Pasted image 20240712161207.png]]
we can see that the maximum **mean earnings** occur at 200 kits produced no matter what the demand is for a certain week

if we change the probability of demand being 200 from 0.25 to 0.05 and increasing the probability for 50 to 0.6, the following graph appears showing 50 to be the optimal number of kits produced
![[Pasted image 20240712161013.png]]

## Code used:
* Dependencies - numpy, matplotlib, python 3.5
```
import numpy as np
import matplotlib.pyplot as plt
def gothru(x,p1,p2,p3,p4):
  if 200>=x>=100:
    return p1*(x*80)+p2*(100*80-25*(x-100))+p3*(50*80-25*(x-50))+p4*(-25*x)
  elif 100>x>=50:
    return p1*(x*80)+p2*(100*80)+p3*(50*80-25*(x-50))+p4*(-25*x)
  elif 50>x:
    return p1*(x*80)+p2*(100*80)+p3*(50*80)+p4*(-25*x)
x = np.linspace(0,200,100)
y = []
for i in x:
  y.append(gothru(i,0.25,0.3,0.4,0.05))
y = np.array(y)
plt.plot(x,y)
plt.xlabel("units produced")
plt.ylabel("profits")
plt.show()
```
