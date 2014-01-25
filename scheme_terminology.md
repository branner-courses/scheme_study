## Scheme terminology

### Scheme proper

 * **atom**: immutable and unique
 * **car**: first member of lat ("Contents of the Address part of Register")
 * **cdr**: remainder of lat ("Contents of the Decrement part of Register")
 * **to cdr down a list**: to "[take] successive `cdr`s to visit each `cons` of the list, or by using any of a number of higher-order functions to map a function over a list" ([Wikipedia article](https://en.wikipedia.org/w/index.php?title=Lisp_%28programming_language%29&printable=yes), accessed 20140124)
 * **cons**: constructs memory object pair
 * **lat**: list of atoms
 * **member**: element of a list
 * **rember**: remove member
 * **s-expression**: nested tree-structure ("symbolic expression", parenthesized lists; note "dotted-pair notation")
 * **define**: name a function
 * **nil**: the empty list (also `()`); uniquely, both an atom and a list
 * **pair**: each cell of a list, consisting of the pointers `car` and `cdr`
 * **symbolic atom**: ...
 * **lambda**: ...
 * **append**: ...
 * ****: 

### Terminology used in passing

 * **homoiconic**: "the primary representation of program code is the same type of list structure that is also used for the main data structures" ([Wikipedia article](https://en.wikipedia.org/w/index.php?title=Lisp_%28programming_language%29&printable=yes), accessed 20140124)
* **variadic**: "able to take any number of arguments", also "n-ary" ([Wikipedia article](https://en.wikipedia.org/w/index.php?title=Lisp_%28programming_language%29&printable=yes), accessed 20140124)
* **destructive** (of a function): altering its own arguments; marked with `!` in Scheme ([Wikipedia article](https://en.wikipedia.org/w/index.php?title=Lisp_%28programming_language%29&printable=yes), accessed 20140124)
* **bang**: exclamation point ([Wikipedia article](https://en.wikipedia.org/w/index.php?title=Lisp_%28programming_language%29&printable=yes), accessed 20140124)

[end]