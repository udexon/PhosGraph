# PhosGraph MasakNet


1. "Masak" is the Malay word for "cooking". The aims of this project inclulde:

- to help the people who are cooking at home (due to the current COVID19 pandemic lockdown), to sell and deliver the food to nearby customers.
- to arrange expert chefs to conduct cooking classes, online or off line, to train the people who are cooking at home.


2. Why does a cook need another database?

No body needs another database. 

BUT, everyone just needs ___ONE DATABASE___ that can be used to ___store and search any data___.

The primary obstacle in realizing such a universal database has been the lack of a decentralized user authentication protocol. 

Almost all database systems deployed so far rely on some forms of centralized user authentication.

We will try to explain the ideas behind this universal database in the language that a cook, or non programmers, may understand, as his (her) profession represents one of our primary targets.

3. In existing database systems, primarily SQL type, or even some graph database management systems, the decision to create certain fields of data (e.g. name, color of hair, address etc.) is centralized, or more specifically, is made amongst administrators running the database systems, usually within one or more related companies, BUT NOT by USERS.

Experienced programmers may scream upon reading this &mdash; How on Earth is it possible that the decision to create certain fields of data can be made by USERS?

Welcome to Decentralized Graph Database (DGDB).

4. In the following articles, we have demonstrated the examples of Decentralized User Authentication (DUA):

- https://github.com/udexon/PhosChat/blob/master/README.md

- In an earlier article, we demonstrated DUA using Websocket:
  - https://github.com/udexon/XIDT/blob/master/Greet_Secret_Phrase.md

5. In a previous article, we demonstrated how we implemented a [JavaScript function `U()`](https://github.com/udexon/PhosGraph/blob/master/README.md#javascript-function-u-sending-json-string-to-back-end) which sends a JSON string, encoding a general data object, to the back end, which can serve as a Decentralized Graph Database (DGDB) server:

- https://github.com/udexon/PhosGraph/blob/master/README.md

Readers may ask,

- What is so special about about [JavaScript function `U()`](https://github.com/udexon/PhosGraph/blob/master/README.md#javascript-function-u-sending-json-string-to-back-end)?

ANSWER: It is special _BECAUSE the front end has been "decentrally authenticated"_. As such, the front end has been granted _the right to create data fields_, stored as an JavaScript Object.

This fundamentally changes the roles of a "database management server" (DBMS), where conventionally in SQL DBMS, the data fields have been predetermined and as such, programs have been written to deal with predetermined data fields; while in DGDBMS, the server needs to deal with non-deterministic data fields.

In practice, User A may enter the following JSON:
```
{name: 'Do Re Mi', age: 'born 1987', city: 'Ampang', 
specialty: 'Rendang Special', fees: 'MYR 50 / hour'}
```

User B may enter the following JSON, with different "keys" (data fields) from User A:
```
{surname: 'Mi Fa So', age: 'born 1977', state: 'Pahang', 
hobby: 'Running', fees: 'MYR 500 / hour'}
```

6. Readers may ask,

- Based on the examples of data by User A and User B, does it not make it more complicated to process such non-deterministic data?

DEFINITELY. However, DGDBMS itself offers a solution &mdash; delegating and decentralizing contributions by programmers.

By "delegating and decentralizing", we contrast them with conventional organization model, where only programmers hired or contracted by one or related companies may contribute to codes for processing (sort, delete, search etc.) the database. With DGDBMS, programmers who are unaffiliated with the owner of the DGDBMS server, may contribute to codes for processing the database. This is possible as unaffiliated programmers can be "decentrally authenticated" just like how the Users are. This opens up the possibilities of instead of having half a dozen programmers (say) hired or contracted by a company using SQL DBMS, literally thousands of unaffiliated but decentrally authenticated programmers may contribute to coding.


7. _In a graph database network, there is no central authority. Every server exists as an equal peer to others._

As such, the database stored on one DGDBMS server becomes yet another node from the perspective of the whole network.

At present, even though MAGA+F (Microsoft Apple Google Amazon Facebook) may be running their own centralized database, when the Universal DGDBMS (U-DGDBMS) grows in size, MAGA+F will be forced to join U-DGDBMS. MAGA+F may want to retain central control to "their" data (not technically "theirs", but "users'", due to "government decrees"), but they can also create interfaces to share data with U-DGDBMS as ___EQUAL PEERS___.

<hr>


Unique selling points:
- Source data from anywhere, social media, files, friend's comments, not restricted by owner of website.
- Better search facilities, due to collective contributions by free software programmers. 


Deniability and Undeniability using Asymmetric Cryptography

A person may not be forced to admit to, or otherwise, his (her) ownership of a private key, or his (her) action of using the private key at a particular time, place or in a network connection.

The state may pass laws, however, to forcibly remove servers (virtual or physical) which no human owners (including companies) have claimed ownership. 





Automatic expire and purge.

Each record should show last authorized time.

Outlaw or ban unauthorized data servers. Servers can be removed by police if no owner claims. Claim ownership using private key.

Make money from update authorization.
