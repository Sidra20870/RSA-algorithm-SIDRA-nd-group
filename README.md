<!DOCTYPE html>
<html>
<head>
</head>
<body>
     <div style="background-color:black;color:white;padding:20px;">
          <h1> DM 103348: Graph theory using SNA (social network analysis) </h1>
     <h3> Project Members </h3>
          <table style="width:100%">
  <tr>
    <th>Student Id</th>
    <th>Student Name</th> 
  </tr>
  <tr>
       <td><b>63986</b></td>
       <td><b>Sidra Usman(leader)</b></td>
  </tr>
  <tr>
    <td>63813</td>
    <td>Muhammad Ammar Haider</td>
  </tr>
  <tr>
    <td>63650</td>
    <td>Dua Javeria</td>
  </tr>
  <tr>
    <td>63814</td>
    <td>Muhammad Saqlain</td>
  </tr>
  <tr>
    <td>63761</td>
    <td>Humaira Noor</td>
  </tr>
            
</table>

<h2> Project Description </h2>
<p style="background-color:Tomato;"> SNA: Network is a bundle of modules for network algorithms, specifically designed for the needs of Social Network Analysis (SNA), but can be used for any other graph algorithms. It represents a standard directed and weighted network, which can also be used as an undirected and/or unweighted network of course.
We are looking forward to get a social data and find the relationship between the people using SNA graph theory concept 
Relationship includes,knowing a user which is connected to maximum or minimum number of other users, mutual connections, connection of each employee etc.
SNa: is the process of investigating social structures through the use of networks and graph theory. it is the characterized network structures in terms of nodes or things with in the network and the ties and edges relationship that connect them.


</p>

<h2>Discrete Math Concepts Used </h2>
<ul>
     <li>*Graph theory using social network analysis</li>
     <li>*Analyze any data from network social media</li>
     <li>*Long time existence</li>
     <li>*Mapping :</li>
     <ul>
          <li> * Relation or information between</li>
          <ul>
               <li>* People</li>
               <li>* Team </li>
               <li>* Organization</li>
          </ul>
     </ul>
      <li><Facebook Network</li> 
      <ul> Facebook is widely used social networking site. We got datasheet of Facebook users which are connected to other users. We came up with our project to get to know about users and and their connections to users, such as mutual friends, connected friends etc </ul>
     <li><b> Example: Code </b></li> 
 <ul>
 import networkx as nz
G_symmetric = nz.Graph()
G_fb = nz.read_edgelist('facebook_combined.txt', create_using = nz.Graph(), nodetype=str) </ul>
 <li> Find Edges</li> 
 <ul> We can check total no of edges and and between 2 vertices and line join between 2 nodes called edge. </ul>
 <li> Find Nodes </li>
     
 <ul>*We can check total no of nodes and all total nodes in our graph like set of vertices </ul>
 <ul>*Path finding concept</ul>
 <ul>*Undirected graph as we haven't use weight</ul>
 <ul>*Neigbour nodes </ul> 
 <ul>*Complete information from facebook sheet </ul> 
 <ul>*Finding closure </ul>
 
</ul>
 
 
 
    
 
 <h2> Problems Faced </h2>
<h3> Problem Faced 1: Built-in Functions. </h3>
<p>
     1) we have use networkx(library) built-in functions which were very difficult to understand but with the help of internet and understand their meta data and overcome this problem.</p></BR>
<BR>    
<h3> Problem Faced 2: Communication Problem: </h3>
<p>
   2) We were facing communication problem among project partners beside this, this library contain limit functions which cause us to think how to distribute functions between the partners, So we decided each partner will do 2-3 functions.</p></BR>

<BR>
<h3> Problem Faced 3:  Social organization Data: </h3>
<p>
     3) we never had an experince of importing any social organization data into our project.finding and importing data took our huge      time.</p> </BR>
<h2> References </h2>
https://networkx.github.io/documentation/stable/reference/functions.html<br>
https://www.datacamp.com/community/tutorials/social-network-analysis-python<br>
https://www.python-course.eu/graphs_python.php<br>
https://metacpan.org/pod/SNA::Network

</div>

</body>
</html>
