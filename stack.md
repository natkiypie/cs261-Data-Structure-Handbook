
<h1>The Stack Abstract Data Type</h1>

<p>A <strong>stack</strong> is an ordered collection of items where the addition of new items and the removal of existing items always takes place at the same end. The base of the stack is significant since items stored in the stack that are closer to the base represent those that have been in the stack longest. The most recently added item is the one that is in position to be removed first. This ordering principle is sometimes called <strong>LIFO</strong>, last-in first-out. It provides an ordering based on length of time in the collection. Stacks are fundamentally important, as they can be used to reverse the order of items. The order of insertion is the reverse of the order of removal.</p>

<h1>In Memory</h1>
<p>In memory, x looks like this:</p>

<img src="" width="500">

<h1>Basic Operations</h1>

<ul>
  <li><strong>push(item)</strong> - adds a new item to the top of the stack. It needs the item and returns nothing.
  <li><strong>pop( )</strong> - removes the top item from the stack. It needs no parameters and returns the item. The stack is modified.
  <li><strong>peek( )</strong> - returns the top item from the stack but does not remove it. It needs no parameters. The stack is not modified.
  <li><strong>is_empty( )</strong> - tests to see whether the stack is empty. It needs no parameters and returns a boolean value.
  <li><strong>size( )</strong> - returns the number of items on the stack. It needs no parameters and returns an integer.
</ul>

<h1>Performance</h1>

<ul>
  All operations except <strong>size( )</strong> can be performed in O(1) time. Worst case, size() runs at O(n).
</ul>

<h1>Use Cases</h1>

<ul>
  <li>Maintaining function calls
  <li>String reversal
  <li>Balanced paranthesis
  <li>Back functionality in web browsers
</ul>

<h1>Example</h1>

![](gif/x.gif)

<p>&copy; Nathaniel Pierce. All rights reserved.</p>
