Download Link: https://assignmentchef.com/product/solved-comp352-assignment3-program
<br>
Submit source code, design and any explanation to EAS<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>. Do it in Java. Do not use java’s search or sort methods. Do not use any java pre-built data structures besides arrays! Do not use Java’s Collections or Subclasses!

This assignment has a significant design component. You will use UML class diagrams and text to explain your decisions inside the diagrams, as well as any additional decisions. Do the design first! Read the <strong><sub>whole </sub></strong>assignment before you start.

<strong>Don’t use packages! </strong>Using packages is generally good, but is a pain when I want to test all of you easily and you make other minor changes. <strong><sub>Don’t</sub></strong>

<strong>deviate from the file names indicated! </strong>Huffman.java and ATree.java That includes renaming the file, but leaving the class inside it the same. You may include other files, and those files may be in packages.




<strong>Grade: </strong>30%

<ol>

 <li>Designing a flexible tree structure

  <ul>

   <li>Design a tree structure that you will implement and subclass to solve both the Huffman Coding Problem and either the AVL or Splay Tree problem.</li>

   <li>Include a class diagram showing all the supporting classes of this tree structure.</li>

   <li>Explain your decisions.</li>

   <li>Include a class diagram showing how you Huffman Coding implementation will extend your general tree structure</li>

   <li>Explain your decisions textually</li>

   <li>Include a class diagram showing how either your AVL Tree or Splay Tree implementation will extend your general tree structure.</li>

   <li>Explain your decisions textually</li>

   <li>Explain why you chose either the AVL Tree or the Splay Tree to solve question 3, referencing your diagrams and decisions as is appropriate.</li>

  </ul></li>

 <li>Implement a Huffman Coding Tree based off of the design in question 1.

  <ul>

   <li>Your tree should build itself using</li>

  </ul></li>

</ol>

<a href="https://users.encs.concordia.ca/~sthiel/comp352/Jabberwock.txt">https://users.encs.concordia.ca/~sthiel/comp352/Jabberwoc</a>k. <a href="https://users.encs.concordia.ca/~sthiel/comp352/Jabberwock.txt">txt</a>

<ul>

 <li>Include the characters for spacing as well as all punctuation, but not line breaks.</li>

 <li>You should not make encoding for characters not found in the source text, and I will not use any such characters while testing your code.</li>

 <li>When Two characters with the same weight are merged into one subtree, your program should choose for the left child, the element that came first in the source material.</li>

 <li>When two subtrees with the same weight are merged into one subtree, your program should choose for the left child, the element that came first in the priority queue or ordered list you were using to build the tree.</li>

 <li>Using the command line, your program should be called as java Huffman &lt;source&gt;</li>

 <li><strong><sub>&lt;source&gt; </sub></strong>will be the name of the local file to be loaded to built your Huffman Tree</li>

 <li>Upon starting, a frequency table will be built. Your program should listen to stdin (you may use Scanner) and encode any line entered (terminated by a line break) and output the encoded version using 1s and 0s (vs. padded ASCII).</li>

 <li>Your program should multiple lines to be entered, encoding each one as it is entered.</li>

</ul>

<ol start="3">

 <li>Implement either an AVL Tree or a Splay tree based off of the design in question 1.</li>

</ol>

<ul>

 <li>Using the command-line, your program should be called as java ATree &lt;source&gt;</li>

 <li><strong><sub>&lt;source&gt; </sub></strong>will be the name of the local file to be loaded that contains operations</li>

 <li>Your program should output the following statistics after all operations are processed:

  <ul>

   <li>The total number of comparisons.</li>

   <li>The total number of times a node’s parent changes (including new nodes getting their first parent, and removed nodes “losing their parent”).</li>

   <li>The total number of find operations</li>

   <li>The total number of add operations • the total number of remove operations.</li>

  </ul></li>

 <li>The operations in the source file will be one-per-line and will consist of the letters a,r or f, representing add, remove or find respectively, followed by 3 digits, the value for the node.</li>

 <li>The sample source file that your should run your code against is</li>

</ul>

<a href="https://users.encs.concordia.ca/~sthiel/comp352/Operations.txt">https://users.encs.concordia.ca/~sthiel/comp352/Operation</a>s.

<a href="https://users.encs.concordia.ca/~sthiel/comp352/Operations.txt">txt</a>

<ul>

 <li><strong><sub>note: </sub></strong>The tree starts out empty and is filled by the operations.txt (or similar file). Your program should deal properly with trying to find or delete nods that aren’t in the tree.</li>

</ul>

<ol start="4">

 <li>Textual Responses, Keep in a separate file for easy reading by me! All responses should not exceed one page (10pt font, 1inch margin, for you weirdos)</li>

</ol>

<ul>

 <li>Huffman

  <ul>

   <li>Look up the file: <a href="https://users.encs.concordia.ca/~sthiel/comp352/RandomStrings.txt">https://users.encs.concordia.ca/~sthiel/ </a><a href="https://users.encs.concordia.ca/~sthiel/comp352/RandomStrings.txt">comp352/RandomStrings.txt</a></li>

   <li>Encode the string associated with your student id and record the result here.</li>

   <li>Describe what percentage fewer bits were used than the fixedlength ASCII encoding would have taken.</li>

   <li>Indicate whether you feel that the encoded string matched the source text frequencies, and provide your reasoning.</li>

  </ul></li>

 <li>Advanced Trees

  <ul>

   <li>Provide the output you recorded based on the Operations file provided in question 3</li>

   <li>Explain whether you feel that your initial design decision was correct when choosing either AVL or Splay trees, given that you have now implemented and tested. Explain anything you have learned through implementing and testing that would affect any future designs.</li>

  </ul></li>

</ul>

<a href="#_ftnref1" name="_ftn1">[1]</a> <a href="https://fis.encs.concordia.ca/eas/">https://fis.encs.concordia.ca/eas/</a>