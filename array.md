
<h1>The Array Abstract Data Type</h1>

<p>An <strong>array</strong> is a data structure used to store homogeneous elements at contiguous locations in memory that are accessable by index. In low-level programming languages, the size of an array must be provided before it can be used to store data. In high-level languages, such as Python, size can be dynamically modified at runtime. These types of arrays are known as <strong>dynamic arrays</strong>. Once filled, a dynamic array can allocate a bigger chunk of memory, copy the contents from the original array to this new space, and continue to fill the available slots. The elements stored in an array can be anything from primitives types such as integers to more complex types like instances of classes.</p>

<h1>In Memory</h1>
<p>In memory, an array looks like this:</p>
<img src="" width="500">

<h1>Common Operations</h1>

<ul>
  <li><strong>Access</strong> - access element using the given index
  <li><strong>Search</strong> - search for an element using given the index or by value
  <li><strong>Insert</strong> - add an element at the given index
  <li><strong>Delete</strong> - delete an element at the given index
</ul>

<h1>Performance</h1>

<ul>
  <li><strong>Accessing Time</strong>: O(1) - this is possible because elements are stored at contiguous locations
  <li><strong>Search Time</strong>: O(n) - for sequential search. O(log n) - for binary Search (if the array is sorted)
  <li><strong>Insertion Time</strong>: O(n) - the worst case occurs when insertion happens at the beginning of the array and requires shifting of all elements
  <li><strong>Deletion Time</strong>: O(n) - The worst case occurs when deletion happens at the beginning of the array and requires shifting all elements
</ul>

<h1>Use Cases</h1>

<ul>
  <li> you need indexed/random access to elements
  <li> you need speed when iterating through all the elements in sequence
  <li> you need speed when iterating through all the elements in sequence
  <li> memory is a concern. Filled arrays can take up less memory than other data structures (each element in the array is just the data).
</ul>

<h1>Example</h1>

![](gif/x.gif)


<p>&copy; Nathaniel Pierce. All rights reserved.</p>

