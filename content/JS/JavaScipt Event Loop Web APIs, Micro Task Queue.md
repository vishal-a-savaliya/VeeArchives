![[Pasted image 20240820142922.png]]

JavaScript Engine has
1 Call Stack
2 Heap

![[Pasted image 20240820143141.png]]

JS is a single threaded

### Web API
 -> Call Base API goes to the task Queue
 -> Promise based API get to Microtask Queue
 
![[Pasted image 20240820144630.png]]

The First preference is given To microtask Queue Over Task Queue, Event Loop make sure that before moving to Task queue The Microtask Queue is Empty

![[Pasted image 20240820144721.png]]