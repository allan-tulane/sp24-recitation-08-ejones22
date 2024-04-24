# CMPS 2200 Recitation 08

## Answers

**Name:**____Emma Jones_______
**Name:**_________________________


Place all written answers from `recitation-08.md` here for easier grading.



- **1b)**
Work: O(V + E log(V)) , Span: O(V log(V))


- **2b)**
path = []

while parents[destination] is not None:
    path.append(parents[destination])
    destination = parents[destination]

return ''.join(path[::-1]) 

- work: O(n) , span O(n)