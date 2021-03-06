# Stacks and Queues

# What is a Stack ? 
A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.


#### Push

> *Nodes or items that are put into the stack are pushed.*


#### Pop

> *Nodes or items that are removed from the stack are popped. When you attempt to pop an empty stack an exception will be raised.*
 
> **Top - This is the top of the stack.**

> *IsEmpty - returns true when stack is empty otherwise returns false.*
 


## Stacks concepts:

###  FILO

**First In Last Out**

> *This means that the first item added in the stack will be the last item popped out of the stack.*

### LIFO

**Last In First Out**

> *This means that the last item added to the stack will be the first item popped out of the stack.*


#### Push O(1)
> *Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time no matter how many Nodes (n) you have in the stack.*


#### Pop O(1)
> *When conducting a pop, the top Node will be re-assigned to the Node that lives below and the top Node is returned to the user.*

