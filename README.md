# Min_Cost_Arborescence
Algorithm to find minimum spanning tree in a directed graph. <br/>
# Input Format
First line: Number of Test Cases T and then follows their description <br/>
For each test case, <br/>
first row indicate N M s (single space separated) where <br/>
-> N is number of vertices in directed graph where vertices are labelled 1 to N (not 0 indexing) <br/>
-> M is the number of edges and <br/>
-> s is the index of source vertex <br/>
And then M rows mentioning u v w(u,v) (single space separated, where u and v are vertex ids and w is <br/>
weight, Safely assume all edge weights are non-negative, else print -1 for the output)

# Output Format
T rows corresponding to T test cases <br/>
Output row for each test case has 2N+1+1 entries (all single space separated) where <br/>
-> first entry is the total sum of min cost arborescence <br/>
-> and then N entries corresponding to vertices V1, V2, V3..., VN providing the distance of i-th vertex from the
source vertex s. (Indicate -1 if unreachable) <br/>
and then Symbol # and then N entries (corresponding to vertices V1, V2, V3..., VN) providing the label of the parent node through <br/>
which one reaches i-th vertex (basically second last node in path from source vertex to that i-th vertex. (Indicate <br/>
0 if no parent i.e. for source vertex and -1 if vertex i not reachable)
