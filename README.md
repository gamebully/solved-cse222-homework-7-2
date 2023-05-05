Download Link: https://assignmentchef.com/product/solved-cse222-homework-7-2
<br>
<strong><u>PART 1:</u></strong>

Provide two partial implementations of NavigableSet interface:

<ol>

 <li>Implement following methods of NavigableSet interface using skip-list a. insert

  <ol>

   <li>delete</li>

   <li>descendingIterator</li>

  </ol></li>

 <li>Implement following methods of NavigableSet interface using AVL tree a. insert

  <ol>

   <li>iterator</li>

   <li>headSet</li>

   <li>tailSet <strong><u>PART 2:</u></strong></li>

  </ol></li>

</ol>

Write method that takes a BinarySearchTree and checks whether the tree is




<ol>

 <li>an AVL tree</li>

 <li>a Red-Black tree (Suppose BinarySearchTree has a method isRed which returns a boolean value which indicates whether the root node is a red node or not.)</li>

</ol>







<strong><u>PART 3:</u></strong>

Compare insertion performance of the following data structures.

<ul>

 <li>Binary search tree implementation in the book</li>

 <li>Red-Black tree implementation in the book</li>

 <li>2-3 tree implementation in the book</li>

 <li>B-tree implementation in the book</li>

 <li>Skip list implementation in the book</li>

</ul>




For each data structure,

<ul>

 <li>Construct an instance of each data structure by inserting a collection of randomly generated (non-repeating) numbers. Perform this operation 10 times for 10.000, 20.000, 40.000 and 80.000 random numbers (10 times for each). So, you will have 10 instances for each data structure and each different size (i.e., 200 instances in total).</li>

 <li>Compare the experimental run-time performance of the insertion operation for the data structures above as follows:

  <ul>

   <li>Insert 100 extra random numbers into the structures you built and measure the running time</li>

   <li>Calculate the average running time for each data structure and problem size (i.e., number of elements in data structure). o Draw a graph for running-time vs problem size.</li>

   <li>Compare the running times and their increase rate.</li>

  </ul></li>

</ul>


