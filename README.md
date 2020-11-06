# 50.004-ALU-Check-off
# This Readme File serves as justification for all possible test cases in each component of ALU
## It contains a folder only which has all of our work inside.
### Compare unit justification
There would be nine test cases for the compare unit and three cases for each compare unit. 
##
**COMPEQ**
###### *value == value* 
true
###### *bigValue == smallValue* 
false
###### *smallValue == bigValue* 
false
##
**CMPLE**
###### *value == value* 
false
###### *smallValue >= bigValue* 
false
###### *smallValue <= bigValue* 
true
##
**CMPLT**
###### *value == value* 
false
###### *smallValue > bigValue* 
false
###### *smallValue < bigValue* 
true

### Adder unit justification
###### Overflow can never happen if two operands have differnt signs and it's only possible in operands with the same signs.
There would be four cases for addiction only
##
###### *zero+zero no overflow* 
###### *positive+positive no overflow* 
###### *positive+positive overflow* 
###### *positive+negative never overflow(same for negative+positive by swaping a,b position)* 


### Subtractor unit justification

There would be four cases for subtarctor only
##
###### *zero-zero no overflow* 
###### *positive-positive never overflow(same for negative-negative by swaping a,b position)* 
###### *negative-positive overflow* 
###### *negative-positive no overflow* 


### Boolean unit justification
###### We have AND, NAND, OR, NOR, XOR, A six gates in total

### Multiplier unit justification
There would be seven cases in total
###### *postive multiplies postive no overflow*
###### *postive multiplies postive  overflow*
###### *negative multiplies negative no overflow*
###### *negative multiplies negative overflow*
###### *postive multiplies negative no overflow*
###### *postive multiplies negtive overflow*
###### *zero multiplies zero no overflow*

### Shifter unit justification
###### basically shifer for this 16bit ALU would be able to shift at most 15bits.In specific, any value and sum of among 2^0, 2^1, 2^2,2^3.
