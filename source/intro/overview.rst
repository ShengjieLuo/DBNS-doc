=================================================
Architecture
=================================================

This chapter is a short explanation to our DBNS system. The detailed description of the system architecture would be included in the following chapters.

DBNS system is composed of 4 parts:

Information Layer
^^^^^^^^^^^^^^^^^
Information Layer: Collect the package from the NIC and resolve the package by PCAP components.
|layer1|

Platform Layer
^^^^^^^^^^^^^^
Platform Layer: An online stream computing platform to distribute the package data into different database. Some online statitic process is finished here to cutoff the overload in following steps. 
|layer2|

Analysis Layer
^^^^^^^^^^^^^^
Analysis Layer: Online analysis, which provides report each minute, and offline analysis, which provides report each hour are main part of this layer. DBNS takes a duty of network monitor and problem detection. 
|layer3|

Display Layer
^^^^^^^^^^^^^
Displayer Layer: Well-designed web UI for users to employ the analysis result
|layer4|


.. |layer1| image:: https://github.com/ShengjieLuo/DBNS/blob/master/doc/images/layer1.jpg
.. |layer2| image:: https://github.com/ShengjieLuo/DBNS/blob/master/doc/images/layer2.jpg
.. |layer3| image:: https://github.com/ShengjieLuo/DBNS/blob/master/doc/images/layer3.jpg
.. |layer4| image:: https://github.com/ShengjieLuo/DBNS/blob/master/doc/images/layer4.jpg
