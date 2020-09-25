Automatic expire and purge.

Each record should show last authorized time.

Outlaw or ban unauthorized data servers. Servers can be removed by police if no owner claims. Claim ownership using private key.

Make money from update authorization.

MasakNet

Why does a cook need another database?

No body needs another database. 

Everyone just need one database that can be used to store and search any data.

The primary obstacle in realizing such a universal database has been the lack of a decentralized user authentication protocol. 

Almost all database systems deployed so far rely on some forms of centralized user authentication.

We will try to explain the ideas behind this universal database in the language that a cook, or non programmers, may understand, as his (her) profession represents one of our primary targets.

In existing database systems, primarily SQL type, or even some graph database management systems, the decision to create certain fields of data (e.g. name, color of hair, address etc.) is centralized, or more specifically, is made amongst administrators running the database systems, usually within one or more related companies, BUT NOT by USERS.

Experienced programmers may scream upon reading this &mdash; How on Earth is it possible that the decision to create certain fields of data can be made by USERS?

Welcome to Decentralized Graph Database (DGDB).

In the following articles, we have demonstrated the examples of Decentralized User Authentication (DUA):

- https://github.com/udexon/PhosChat/blob/master/README.md

- In an earlier article, we demonstrated DUA using Websocket:
  - https://github.com/udexon/XIDT/blob/master/Greet_Secret_Phrase.md

In a previous article, we demonstrated how we implemented a [JavaScript function `U()`](https://github.com/udexon/PhosGraph/blob/master/README.md#javascript-function-u-sending-json-string-to-back-end) which sends a JSON string, encoding a general data object, to the back end, which can serve as a Decentralized Graph Database (DGDB) server:

- https://github.com/udexon/PhosGraph/blob/master/README.md

Readers may ask,

- What is so special about about [JavaScript function `U()`](https://github.com/udexon/PhosGraph/blob/master/README.md#javascript-function-u-sending-json-string-to-back-end)?

ANSWER: It is special _BECAUSE the front end has been "decentrally authenticated"_. As such, the front end has been granted _the right to create data fields_, stored as an JavaScript Object.


Unique selling points:
- Source data from anywhere, social media, files, friend's comments, not restricted by owner of website.
- Better search facilities, due to collective contributions by free software programmers. 


Deniability and Undeniability using Asymmetric Cryptography

A person may not be forced to admit to, or otherwise, his (her) ownership of a private key, or his (her) action of using the private key at a particular time, place or in a network connection.

The state may pass laws, however, to forcibly remove servers (virtual or physical) which no human owners (including companies) have claimed ownership. 

