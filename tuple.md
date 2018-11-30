
<h1>The Tuple Abstract Data Type</h1>

<p>A <strong>tuple</strong> is similar to an array in that it stores elements at contiguous locations in memory that are accessable by index. However, tuples usually contain heterogenious elements that are immutable (fixed). Changing the values of or removing items in a tuple is not possible. However, it is possible to take portions of existing tuples to create new ones. Because of these few but important differences between tuples and arrays, tuples are often used in different situations for different purposes.</p>

<h1>In Memory</h1>

<p>In memory, a tuple looks like this:</p>
<img src="" width="500">

<h1>Common Operations</h1>

<ul>
  <li><strong>Access</strong> - access element using the given index or access a range of items stored in the tuple
  <li><strong>Search</strong> - search for an element using given the index or by value
</ul>

<h1>Performance</h1>

<ul>
  <li><strong>Accessing Time</strong>: O(1) - this is possible because elements are stored at contiguous locations
  <li><strong>Search Time</strong>: O(n) - for sequential search. O(log n) - for binary Search (if the tuple is sorted)
</ul>

<h1>Use Cases</h1>

<ul>
  <li>passing a string of parameters from one program to another
  <li>representing a set of value attributes in a relational database
  <li>you want the values in the collection to remain constant
</ul>

<h1>Example</h1>

![](gif/x.gif)

<p>&copy; Nathaniel Pierce. All rights reserved.</p>

