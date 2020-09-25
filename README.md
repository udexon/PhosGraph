# PhosGraph
PhosGraph: Decentralized Graph Database

A detailed introduction concerning the source files and basic components of PhosGraph and PhosChat was given in a previoius article:

- https://github.com/udexon/PhosChat/blob/master/README.md

In PhosGraph, we have modified the `CHAT()` function from PhosChat to be a more general function `U()` which sends a JSON string to the back end:

```js
function U(j) // Update, U of CRUD
{
    var d = new Date();
    console.log(d.toISOString());   
    B(btoa(JSON.stringify(j)) +" update")
}
```

To update a JSON record, the following commands are entered in the browser console (figure 1) and the results are shown in figure 2:

```js
c = new JSEncrypt()
B_AUTH(c)
B("foxy nick")
B("SESSION: s:")
S[S.length-1].response
U({name: 'Do Re Mi', age: 'born 1987', city: 'Ampang', 
specialty: 'Rendang Special', fees: 'MYR 50 / hour'})
```

- Figure 1
<img src="https://github.com/udexon/PhosGraph/blob/master/img/PhG_U.png" width=400>

- Figure 2
<img src="https://github.com/udexon/PhosGraph/blob/master/img/PhosGraph_json.png" width=400>
