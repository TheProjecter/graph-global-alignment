**The package is an interface to compare two graphs.**

The package is methods for comparison of bionetwork.
<p>
The graph global alignment package includes twelve functions, each function needs to be input two graphs’ primary key list (which are nodes’ primary keys) and two adjacency matrices (which are edges between nodes).<br>
<p>
After comparing these two primary key list and two adjacency matrices, it uses default penalty system or user input penalty system to calculate the similarity between two graphs.<br>
<p>
• <b>Inner comparison</b>, only addresses on the overlap parts of two node sequences. It is similar with the INTERSECTION binary operation in set theory.<br>
<p>
• <b>Outer comparison</b> considers all the nodes of two graphs. The similarity is evaluated on the UNION of the two node sets.<br>
<p>
• <b>Left comparison</b> is designed for biased comparison. The function only focuses on one graph, instead of both. The related binary relation in set theory is also called LEFT-TOTAL.<br>
<p>
The package allows user to set transitivity degree of comparison.<br>
<p>
Transitivity is a relation between three elements that, if it holds between the first and second and it also holds the second and third, it must necessarily hold between the first and third.<br>
<p>
The degree of transitivity (K) is to record the depth of transitive. The default degree of transitivity is 1, which means no transitivity is allowed.<br>
<p>
The links on the left are JDoc of packages.