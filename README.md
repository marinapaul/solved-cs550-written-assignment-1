Download Link: https://assignmentchef.com/product/solved-cs550-written-assignment-1
<br>
<h1>Chapter 1</h1>

<ol>

 <li><strong>Q: </strong>Sketch a design for a home system consisting of a separate media server that will allow for the attachment of a wireless client. The latter is connected to (analog) audio/video equipment and transforms the digital media streams to analog output. The server runs on a separate machine, possibly connected to the Internet, but has no keyboard and/or monitor connected.</li>

 <li><strong>Q: </strong>Describe precisely what is meant by a scalable system.</li>

 <li><strong>Q: </strong>What is the difference between a multiprocessor and a multicomputer?</li>

</ol>

<h1>Chapter 2</h1>

<ol start="4">

 <li><strong>Q: </strong>If a client and a server are placed far apart, we may see network latency dominating overall performance. How can we tackle this problem?</li>

 <li><strong>Q: </strong>Consider a chain of processes P1,P2,…,Pn implementing a multitiered client-server architecture.</li>

</ol>

Process Pi is client of process P(i+1), and Pi will return a replay to P(i-1) only after receiving a reply from Pi+1. What are the main problems with this organization when taking a look at the request-reply performance at process P1?

<ol start="6">

 <li><strong>Q: </strong>Consider a BitTorrent system in which each node has an outgoing link with a bandwidth capacity <em>Bout </em>and an incoming link with bandwidth capacity <em>Bin</em>. Some of these nodes (called seeds) voluntarily offer files to be downloaded by others. What is the maximum download capacity of a BitTorrent client if we assume that it can contact at most one seed at a time?</li>

</ol>

<h1>Chapter 4</h1>

<ol start="7">

 <li><strong>Q: </strong>In many layered protocols, each layer has its own header. Surely it would be more efficient to have a single header at the front of each message with all the control in it than all these separate headers. Why is this not done?</li>

 <li><strong>Q: </strong>Consider a procedure <em>incr </em>with two integer parameters. The procedure adds one to each parameter. Now suppose that it is called with the same variable twice, for example, as <em>incr</em>(<em>i</em>, <em>i</em>). If <em>i </em>is initially 0, what value will it have afterward if call-by-reference is used? How about if copy/restore is used?</li>

 <li><strong>Q: </strong>One way to handle parameter conversion in RPC systems is to have each machine send parameters in its native representation, with the other one doing the translation, if need be. The native system could be indicated by a code in the first byte. However, since locating the first byte in the first word is precisely the problem, can this actually work?</li>

 <li><strong>Q:</strong> What trade-off should be made when we decide between a shared memory model and a message passing model? Why does this make shared memory a bad match for a system distributed across the Internet?</li>

</ol>