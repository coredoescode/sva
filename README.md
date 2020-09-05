# sva
The worst data storage standard ever.

#### How do I read this garbled mess of data?
Split the whole chunk by every second `:`.
You will get a bunch of keys:
```
1:A value
2:A different value
```
The number on the left is the proprety ID, everything to the right up to the next colon is it's value.
Proprety ID's are not standard and are defined by the program using SVA.
