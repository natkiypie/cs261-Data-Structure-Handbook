
<h1>The Queue Abstract Data Type</h1>

<p>A <strong>queue</strong> is an ordered collection of items where the addition of new items happens at one end, commonly called the "rear", and the removal of existing items occurs at the other end, commonly called the "front". As an element enters the queue, it starts at the rear and makes its way toward the front, waiting until it is the next element to be removed. The most recently added item in the queue must wait at the end of the collection. The item that has been in the collection the longest is at the front. This ordering principle is sometimes called <strong>FIFO</strong>, first-in first-out.</p>

<h1>In Memory</h1>
<p>In memory, an queue looks like this:</p>
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
  <li><strong>Accessing/Search Time</strong>: O(n) - to access or find an arbitary element stored in a queue requires shifting its contents repeatedly until it is found. The time complexity of this operation depends on the size of the queue and is therefore linear
  <li><strong>Insertion Time</strong>: O(1) - inserting an item into a queue, by definition, only takes place at the back of the queue and is therefore done in constant time
  <li><strong>Deletion Time</strong>: O(1) - similarly, deleting an item from a queue, by definitioin, only takes place at the front of the queue and is done in constant time.
</ul>

<h1>Use Cases</h1>

<ul>
  <li>Any situation where resources are shared among multiple users and served on first come first server basis
  <li>CPU scheduling
  <li>asynchronous data transfer (data not received at same rate as sent)
</ul>

<h1>Example</h1>

![](../../../gif/queue.gif)

<p>&copy; Nathaniel Pierce. All rights reserved.</p>

