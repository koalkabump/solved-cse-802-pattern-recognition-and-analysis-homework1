Download Link: https://assignmentchef.com/product/solved-cse-802-pattern-recognition-and-analysis-homework1
<br>






<strong>Note:</strong>

<ol>

 <li><strong>You are permitted to discuss the following questions with others in the class. However, you <em>must </em>write up your <em>own </em>solutions to these questions. Any indication to the contrary will be considered an act of academic dishonesty. Copying from <em>any source </em>constitutes academic dishonesty.</strong></li>

 <li><strong>A hard-copy of the homework must be submitted by February 3, 12:40 pm. Late submissions will not be graded. In your submission, please include the names of individuals you discussed this homework with and the list of external resources (e.g., websites, other books, articles, etc.) that you used to complete the assignment (if any).</strong></li>

 <li><strong>Code developed as part of this assignment must be included as an appendix to your submission or inline with your solution.</strong></li>

 <li>The <a href="https://www.cse.msu.edu/~rossarun/courses/sp20/cse802/data/imox_data.txt"><strong>IMOX</strong></a> dataset consists of 192 8-dimensional patterns pertaining to four classes (digital characters ‘I’, ‘M’, ‘O’ and ‘X’). There are 48 patterns per class. The 8 features correspond to the distance of a character to the (a) upper left boundary (<em>x</em><sub>1</sub>), (b) lower right boundary (<em>x</em><sub>2</sub>), (c) upper right boundary (<em>x</em><sub>3</sub>), (d) lower left boundary (<em>x</em><sub>4</sub>), (e) middle left boundary (<em>x</em><sub>5</sub>), (f) middle right boundary (<em>x</em><sub>6</sub>), (g) middle upper boundary (<em>x</em><sub>7</sub>), and (h) middle lower boundary (<em>x</em><sub>8</sub>). Note that the class labels (1, 2, 3 or 4) are indicated at the end of every pattern.

  <ul>

   <li>[4 points] Compute and report the mean pattern vector, i.e., the centroid, of <em>each class</em>.</li>

   <li>[4 points] For <em>each class</em>, determine the pattern (i.e., vector) from that class which is the farthest from the class mean. You can use the Euclidean distance metric for this problem.</li>

   <li>[8 points] For <em>each feature</em>, plot the histograms pertaining to the 4 classes. Your output should contain 8 graphs corresponding to the 8 features; <em>each graph </em>should contain 4 histograms corresponding to the 4 classes (choose a bin size of your choice for the histograms). Based on these plots, indicate (a) the <em>features </em>that are likely to be useful for distinguishing the 4 classes, and (b) the <em>classes </em>that are likely to overlap with each other to a great extent. Provide an <em>explanation </em>for your answer.</li>

   <li>[5 points] Assume that each pattern can be represented by features <em>x</em><sub>1 </sub>and <em>x</em><sub>2</sub>. This means, each pattern can be viewed as a point in 2-dimensional space. Draw a scatter plot showing all 192 patterns (use different labels/markers to distinguish between classes). Draw another scatter plot based on features <em>x</em><sub>3 </sub>and <em>x</em><sub>4</sub>. Based on these scatter plots, <em>explain </em>which of the two feature <em>subsets </em>((<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>) or (<em>x</em><sub>3</sub>, <em>x</em><sub>4</sub>)) is likely to be useful for separating the 4 classes.</li>

   <li>[4 points] Assume that each pattern can be represented by features (<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>, <em>x</em><sub>4</sub>). Draw a 3-dimensional scatter plot showing all 192 patterns. Based on this scatter plot, <em>explain </em>which classes overlap with each other to a great extent.</li>

  </ul></li>

 <li>[10 points] What type of learning scheme – supervised, unsupervised, or reinforcement – can be used to address each of the following problems. You must <em>justify </em>your answer.

  <ul>

   <li>Teaching a self-driving rover to navigate the terrain of Mars.</li>

   <li>Given a large set of unknown flowers, discover categories of flowers based on color, geometry, texture and scent of the flowers.</li>

   <li>Determining the identity of a person in a video based on their voice.</li>

   <li>Predicting whether it would rain or not in the next 24 hours based on current weather conditions such as precipitation, humidity, temperature, wind, pressure, etc.</li>

   <li>Given a large set of photos, group all similar looking faces together.</li>

  </ul></li>

 <li>[15 points] Describe each of the following terms with an example: (a) overfitting, (b) loss function, (c) decision boundary, (d) segmentation, (e) invariant representation.</li>

 <li>[20 points] The paper <a href="http://www.jmir.org/2012/5/e130/">Classification Accuracies of Physical Activities Using Smartphone Motion Sen</a><a href="http://www.jmir.org/2012/5/e130/">sors</a> by Wu et al. discusses a pattern classification system that determines the physical activity of an individual based on data gleaned from the iPod Touch.

  <ul>

   <li>Briefly describe this system based on the pattern recognition terminology developed in class: (i) sensors used; (ii) pre-processing of raw data; (iii) features extracted; and (iv) classification scheme. How many features (i.e., <em>d</em>) and classes (i.e., <em>c</em>) are present?</li>

   <li>How was classifier training accomplished? How many patterns were available in the training set? How were the training patterns labeled?</li>

   <li>How was the performance of the pattern recognition system evaluated? What metrics were used to evaluate classifier performance?</li>

   <li>In your opinion, did the proposed pattern recognition system perform well? Why or why not?</li>

  </ul></li>

 <li>[5 points] Consider the following probability density function which is non-zero only in the range 0 <em>≤ x ≤ </em>10: <em>p</em>(<em>x</em>)= <em>K</em>.<em>x</em><sup>3</sup>(10 <em>− x</em>).</li>

</ol>

Here, <em>K </em>is a constant. Determine the value of the constant <em>K</em>.

<ol start="6">

 <li>Consider the problem of classifying two-dimensional patterns of the form <strong><em>x </em></strong>=(<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>)<em><sup>t </sup></em>into one of two categories, <em>ω</em><sub>1 </sub>or <em>ω</em><sub>2</sub>. Using the labeled patterns presented in <a href="https://www.cse.msu.edu/~rossarun/courses/sp20/cse802/data/patterns_labels.txt">this data set</a><a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>, do the following.

  <ul>

   <li>[8 points] Plot the histograms (bin size = 1) corresponding to (<em>x</em><sub>1</sub><em>|ω</em><sub>1</sub>) and (<em>x</em><sub>1</sub><em>|ω</em><sub>2</sub>) in a graph. Also, plot the histograms (bin size = 1) corresponding to (<em>x</em><sub>2</sub><em>|ω</em><sub>1</sub>) and (<em>x</em><sub>2</sub><em>|ω</em><sub>2</sub>) in a separate graph. Is <em>x</em><sub>1 </sub>more discriminatory than <em>x</em><sub>2</sub>?</li>

   <li>[7 points] Plot the two-dimensional patterns in a graph. Use markers to distinguish the patterns according to their class labels. Suppose you have the following decision rule (classifier) to classify a novel pattern <strong><em>x </em></strong>=(<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>)<em><sup>t</sup></em>:</li>

  </ul></li>

</ol>

If <em>x</em><sub>1</sub>+ <em>x</em><sub>2 </sub><em>− </em>15 <em>&lt; </em>0, <strong><em>x </em></strong><em>∈ ω</em><sub>1 </sub>else <strong><em>x </em></strong><em>∈ ω</em><sub>2</sub>.

In the same graph, plot the decision boundary corresponding to this rule. What is the error rate (i.e., the percentage of patterns that are misclassified) when this decision rule is used to classify the patterns in the given data set?

<ul>

 <li>[7 points] Repeat the above after modifying the decision rule (classifier) as follows:</li>

</ul>

If <em>x</em><sub>1</sub>+ <em>x</em><sub>2 </sub><em>− </em>12 <em>&lt; </em>0, <strong><em>x </em></strong><em>∈ ω</em><sub>1 </sub>else <strong><em>x </em></strong><em>∈ ω</em><sub>2</sub>.

<ul>

 <li>[3 points] Which of the two classifiers has performed well on this dataset.</li>

</ul>

<a href="#_ftnref1" name="_ftn1">[1]</a> The text file has 3 columns. The first two columns correspond to the feature vector of a pattern and the third column corresponds to its class label.