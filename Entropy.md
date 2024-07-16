![[Pasted image 20240704094056.png]] 
#thermo 
Suppose we have a reaction forming ammonia from Nitrogen and hydrogen. This reaction is reversible and has an equilibrium. We want to make a function that's at a maximum when equilibrium is achieved
![[Pasted image 20240704093411.png]]
the maximum is where equilibrium is attained


$$\frac{dS}{dt} = \sum mS_i + \frac{\frac{dQ}{dt}}{T} + S_{gen}$$
## Historical perspective
A few hundred years ago, when the entropy equation didn't exist, people were trying to convert all the heat into work because of the industrial revolution and they wanted MAXIMUM work from heat. They were trying to devise motors or engines.

When they added say, 300J of work into an engine, they wanted 300J out. Experimentally, it has been shown that this is impossible. Entropy is a model to explain and predict this phenomenon

>[!note] note
>pointless to expect to understand what entropy is. It's just a model to make predictions and design systems with

## Why 100% efficiency doesn't work out
the equation for a heat engine converting 100% heat to work is 
$$\frac{dS^t}{dt} = 0+300/T+S_{gen}$$
$$Sgen = -300/T$$
This is impossible, since S_{gen} can never be less than 0
Thus it is
>not possible to convert all heat into work


>[!note] note
>This actually raises a lot of odd implications so I don't really understand it yet

## Why the above is OK and not a universe ending idea
It's not possible to transfer heat from a colder object to warmer object without Ws
$$0=0-0+\frac{Q}{T_h}-\frac{Q}{T_c} + S_{gen}$$ (continuing from the train of logic before)
S_gen must be negative now since T_c is lower than T_h
this is impossible

Why it's possible to transfer heat from a hot substance to a cold substance
$$0=0-0+\frac{Q}{T_c}-\frac{Q}{T_h}+S_{gen}$$
Since S_gen here is over 0, it is possible
>[!note] issues
>Where does work come in man??? it should be possible with w_s. so where is that in the statement???? 

## Carnot efficiency
maximum possible work you can get out of a heat engine is when:
$$Q_h/T_h = Q_c/T_c$$
$$0=0-0+Q_h/T_h-Q_c/T_c+S_{gen}$$
S_gen here is 0, this tells us something about max efficiency - occurs when S_gen is 0
>[!happy] happy
>the above notes are stupid. Problem solved. W_s not needed really. Wait what about refrigeration. damnit

## Refrigeration
same condition as carnot efficiency 
forget it. I understand :pray:
![[Pasted image 20240704102602.png]]
## Transfer of heat from higher to lower temperature
>[!A to B]
>imagine there is a container with two sections separated by a material of heat transfer coefficient h, the two sections are labelled A and B.
>	$$S^t_{gen} = Q(\frac{1}{T_b}-\frac{1}{T_a})$$
>	$$S^t_{gen} = h(T_a-T_b)(\frac{1}{T_b}-\frac{1}{T_a})$$

> WHY CAN COP BE MORE THAN 1? for a fridge

This is because heat pumps are not like engines, the work you're putting in isnt geting converted to heat or otherwise, its just causing heat to be transferred from one place to another thus it's possible to cool a room down more than how much work you're putting into it because the work is only needed to satisfy the first law of thermodynamics\

Engines, however cannot have efficiencies more than 100% because you are very literally converting the heat into work

