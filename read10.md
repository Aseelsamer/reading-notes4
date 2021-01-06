# What is a Stack
A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

# Common terminology for stack ?
1-Push  Nodes or items that are put into the stack are pushed
2-Pop  Nodes or items that are removed from the stack are popped.
3-Top This is the top of the stack.
4-Peek you will view the value of the top Node in the stack.
5-isEmpty  returns true when stack is empty otherwise returns false.

Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time no matter how many Nodes (n) you have in the stack.

When adding a Node, you push it into the stack by assigning it as the new top, with its next property equal to the original top.

Popping a Node off a stack is the action of removing a Node from the top. When conducting a pop, the top Node will be re-assigned to the Node that lives below and the top Node is returned to the user.

Peek O(1)
When conducting a peek, you will only be inspecting the top Node of the stack.

Typically, you would check isEmpty before conducting a peek. This will ensure that an exception is not raised. Alternately, you can wrap the call in a try/catch block.

# What is a Queue ?
Common terminology for a queue is ?
1-Enqueue When you add an item to a queue, you use the enqueue action.
2-Dequeue When you remove an item from a queue, you use the dequeue action.
3-Front this is the front/first node .
4-Rear this is the rear/last node .
5-Peek you will view all the value of the fron Node .
6-IsEmpty returns true when queue is empty.



