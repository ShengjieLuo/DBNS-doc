=================================================
Architecture
=================================================

This chapter is a short explanation to our DBNS system. The detailed description of the system architecture would be included in the following chapters.

DBNS system is composed of 4 parts:

Information Layer
^^^^^^^^^^^^^^^^^
Information Layer: Collect the package from the NIC and resolve the package by PCAP components.
image::https://github.com/ShengjieLuo/DBNS/blob/master/doc/images/layer1.jpg

Platform Layer
^^^^^^^^^^^^^^
Platform Layer: An online stream computing platform to distribute the package data into different database. Some online statitic process is finished here to cutoff the overload in following steps. 

Analysis Layer
^^^^^^^^^^^^^^
Analysis Layer: Online analysis, which provides report each minute, and offline analysis, which provides report each hour are main part of this layer. DBNS takes a duty of network monitor and problem detection. 

Display Layer
^^^^^^^^^^^^^
Displayer Layer: Well-designed web UI for users to employ the analysis result
