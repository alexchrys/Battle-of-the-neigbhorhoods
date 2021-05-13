# Battle-of-the-neigbhorhoods

This repository is for the final Capstone project of my IBM Data Science Professional Certification. IBM Watson Studio was used.

<b><u>Scope:</u></b>
Berlin and Hamburg are Germany's two largest cities. While Berlin is counting roughtly 3.8 million residents and Hamburg roughtly 1.8 million, both cities are quite different. Berlin is a mix of cultural, historical and artistic sights. It's an intriguing city that invites people of all backgrounds. Germany’s second largest city, Hamburg, is both typically German and unique in its own way. With a long maritime history, this North Sea port city has a distinct feel from anywhere else in the country and tons of cool things to see and do.

Both cities beeing in the northern part of Germany, there is a great exchange between residents of both cities. This analysis is intended to show which areas of one city resemble those of the other: Berlin and Hamburg.

<b>Data:</b>
Two different kind of data is needed for the comparison.

City neighborhood and respective geographical data: in order to analyse the cities on a detailed level, they need to be divided into differen areas, e.g. neighborhoods, boroughs. Luckily both is available as a Github repro. This data includes 11 rows, of which only state (i.e. Berlin or Hamburg), ZIP-code (10 for Berlin, 22 for Hamburg), latitude and longitude per ZIP-code will be needed. ZIP-codes will be used for dividing both cities into smaller areas. ZIP-code is chosen as it is an unique identifier. In the following this data is cleaned and filtered to what is needed.

The Venue data is gathered using the Foursquare API.
