1. Which city has the highest inefficiency ratio?
According to the program, when run in the terminal, the city with the highest inefficiency ratio
is London, UK. The cables that serve this city include EXA Express, Tata TGN-Atlantic South, Tata TGN-Western Europe,
Circe South, Q&E South, and CrossChannel Fibre. Despite the several sources of strong connectivity,
internet traffic does not necessarily travel in a straight line and can be routed through other major network hubs and servers.
This reasoning may explain why the measured RTT was much larger than the theoretical minimum.

2. Which city is closest to the theoretical minimum? What does that tell you about routing infrastructure there?
Sydney AUS is closest to the theoretical minimum RTT. The reason for this is that the measured RTTs are actually inflated by 
network routing to nearby CDN/edge servers, i.e. other network hubs/servers, rather than the actual destination cities. 
As a result, Sydney's theoretical distance aligns most similarly with the measured latency, resulting in a lower
inefficiency ratio.

3. Your packet to Lagos almost certainly routes through Europe first. Why does Africa route through Europe,
and what would need to change to fix it?
Africa routes through Europe entirely due to historically limited direct intercontinental cable connections
to continents such as North America. On the other hand, Europe contains major internet hub cities including
London, Amsterdam, etc. which contain dense submarine cable connecting points and networking hubs.
As a result, Africa's traffic goes through Europe and then to the rest of the world.
To fix this would require essentially building new submarine cable networks routing from Africa directly to other
continents and countries such as North America, South America, and Austrailia.
