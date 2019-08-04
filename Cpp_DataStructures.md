This document includes breif overview such as supported operations and complexity of C++ containers


## std::array

  
<table>
 <!--Head of the table -->
 <thead> <tr> <th>Type </th> <th>Format </th> <th>Description </th> <th>Complexity </th> </tr> </thead>
 <tbody>
   <!--Constructors -->
   <tr> <td rowspan=1>Constructors</td> <td>array&ltT,n&gt a</td> <td>Create an array, a, of type T with n elements</td> <td align="center">O(1)</td> </tr>
   <!--Iterators -->
   <tr> <td rowspan=8>Iterators</td> <td> a.begin()</td> <td>Returns iterator to beginning of the array</td> <td align="center">O(1)</td>     </tr>
   <tr> <td>a.end()</td> <td>Returns iterator to end of the array</td>	<td align="center">O(1)</td> </tr>
   <tr> <td>a.rbegin()</td> <td>Returns reverse iterator to reverse beginning (i.e. end) of the array</td> <td align="center">O(1)</td></tr>
   <tr> <td>a.rend()</td> <td>Returns reverse iterator to reverse end (i.e. beginning) of the array</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.cbegin()</td> <td>Returns constant iterator to beginning of the array</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.cend()</td> <td>Returns constant iterator to end of the array</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.crbegin()</td> <td>Returns reverse constant iterator to reverse beginning of the array</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.crend()</td> <td>Returns reverse constant iterator to reverse end of the array</td> <td align="center">O(1)</td> </tr>
   <!--Capacity -->
   <tr> <td rowspan=3>Capacity</td> <td rowspan=1>a.size()</td> <td>Returns the size of the array (number of elements)</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.max_size()</td> <td>Returns the size of the array (number of elements, same as a.size())</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.empty()</td> <td>Tests whether the array is empty are not</td> <td align="center">O(1)</td> </tr>
   <!--Accessing elements -->
   <tr> <td rowspan=5>Element Access</td> <td>a[i]</td> <td>Access the i<sup>th</sup> element of the array</td> <td align="center">O(n)</td> </tr>
   <tr> <td>a.at(i)</td> <td>Access the i<sup>th</sup> element of the array (automatically checks the bounds of the array)</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.front()</td> <td>Access the first element of the array</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.back()</td> <td>Access the last element of the array</td> <td align="center">O(1)</td> </tr>
   <tr> <td>a.data()</td> <td>Returns pointer to the first element of the array</td> <td align="center">O(1)</td> </tr>
   <!--Modifiers -->
   <tr> <td rowspan=2>Modifiers</td> <td>a.fill(value)</td> <td>Fill the array with a specified value</td> <td align="center">O(n)</td> </tr>
   <tr> <td>a.swap(array<T>)</td> <td>Swap the content of two arrays</td> <td align="center">O(n)</td> </tr>
  </tbody> <!--End of the body -->
</table> <!--End of the table -->
