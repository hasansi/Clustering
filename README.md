
# Clustering Consulting Project 

Predict the number of hackers involved in hacking a technology firm, based on the data available about the hacks, including information like session time,locations, wpm typing speed, etc. The meta data of each session that the hackers used to connect to their servers are:

* 'Session_Connection_Time': How long the session lasted in minutes
* 'Bytes Transferred': Number of MB transferred during session
* 'Kali_Trace_Used': Indicates if the hacker was using Kali Linux
* 'Servers_Corrupted': Number of server corrupted during the attack
* 'Pages_Corrupted': Number of pages illegally accessed
* 'Location': Location attack came from (Probably useless because the hackers used VPNs)
* 'WPM_Typing_Speed': Their estimated typing speed based on session logs.


Its also known that the hackers taded off the attacks, meaning each hacker mounted roughly the same number of attacks and that there are 3 or less number of hackers.

To answer this question, we should approach this as a (unsupervised machine learning) clustering problem. 
After using the clustering models with 2 and 3 potential clusters, it can be reasonably stated that there were 2 hackers since only in that situation we get equal number of hacking attacks.
