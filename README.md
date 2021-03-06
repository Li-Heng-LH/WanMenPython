# WanMenPython
Python Learning
&nbsp;

### Some Learning Notes ###

##### Python Naming Conventions #####
* Function names should be lowercase, with words separated by underscores as necessary to improve readability.   
* Variable names follow the same convention as function names.
&nbsp;

##### math library ####
* use `**` over `math.pow`
&nbsp;

##### Python Object Reference ####
* `line = 'hello'`  
`line_copy = line`  
`id(line), id(line_copy)` --> (112233, 112233)  
![objec_reference_1.png](Documents/objec_reference_1.png)  

* `line = 'world'`  
`id(line), id(line_copy)` --> (223344, 112233)   
![objec_reference_2.png](Documents/objec_reference_2.png)  
&nbsp;

##### Python List ####
* In Python, **sequence** is the generic term for an ordered set. 
* There are six sequence types: strings, Unicode strings, lists, tuples, buffers, and xrange objects.
* List is **mutable**. 

&nbsp;

##### Python Data Structure ####
* List is a collection which is ordered and changeable. Allows duplicate members.
* Tuple is a collection which is ordered and unchangeable. Allows duplicate members.
* Set is a collection which is unordered and unindexed. No duplicate members.
* Dictionary is a collection which is unordered, changeable and indexed. No duplicate members.
&nbsp;

##### Conditions ####
* `elif` can be from 0 to infinity. 
* `else` is not necessary.  
&nbsp;

##### For Loop ####
A for loop can be used for iterating over : 
* list
* tuple
* dictionary
* set
* string
&nbsp;

&nbsp;
### Python VS Java ###
##### Strings #####

<table>
  <tbody>
    <tr>
      <th></th>
      <th>Python</th>
      <th>Java</th>
    </tr>
    <tr>
      <td>What is it</td>
      <td>Strings are <b>arrays of bytes</b> representing Unicode characters. <br> However, Python does not have a character data type, a single character is simply a string with a length of 1.</td>
      <td>String is an object that represents <b>sequence of char values</b>.</td>
    </tr>
    <tr>
      <td>Mutability</td>
      <td>Immutable</td>
      <td>Immutable</td>
    </tr>
    <tr>
      <td>Concatenation</td>
      <td> string + string</td>
      <td> <ol>
          <li> string + string </li>
          <li> string.concat(string) </li> </ol>
      </td>
    </tr>
    <tr>
      <td> Access elements </td>
      <td> string[] </td>
      <td> string.charAt(int index) </td>
    </tr>
    <tr>
      <td> Slicing </td>
      <td> string [2:5] </td>
      <td> string.substring(2, 5) </td>      
    </tr>
    <tr>
      <td> Length </td>
      <td> len(string) </td>
      <td> string.length()</td>
    </tr>
    <tr>
      <td> Remove white spaces </td>
      <td> string.strip() </td>
      <td> string.trim() </td>
    </tr>
    <tr>
      <td> Formatting </td>
      <td> string.format(value) </td>
      <td> String.format("name is %s",name); </td>
    </tr>
  </tbody>
</table>

Python Strings also: 
* support * operation
* have negative indexing
&nbsp;

&nbsp;
----
### Useful links ###
* [​​​​Jupyter Notebook for Beginners: A Tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)
* [Python Naming Conventions](https://www.python.org/dev/peps/pep-0008/#function-and-variable-names)
* [java vs python data types](https://www.programcreek.com/2012/09/java-vs-python-data-types/)
