# Ground Control

`````````````````````````````````````````````````````````````````
///::---......```````````````````````````````` ``````````````````````````````````````...............
::::---.....```````````````````````````````` .-.-`-```..```````````````````````````````.............
:::---....````````````````````````.-.``--```.///////:/+/:/---....``````````````````````.............
::---....``````````````````````````://::/:..//////////+++++++++++:--..``````````````````............
:---...````````````````````````.///////////////////////+++++++++++ooo+:-```````````````````.........
---...``````````````````````.-////////////////////////+//+++++++++oooo/-.```````````````````........
--...````````````````````.-////////////////////////////+/++++++++oooooo++/.````````````````````.....
-...````````````````````-:/+//////////////////////////+++++++++++oooooooooo:````````````````````....
...````````````````````:++++///////////////////////////++++++++++ooooooooooo+-```````````````````...
..```````````````````-/+++++//////////////////////////+++++++++++ooooooooooooo:````````````````````.
.``````````````````./+++++++//////////////////////////+++++++++++oooooooooooooo/````````````````````
.`````````````````./+++++++++++////////////////////////+++++++++++oooooooooooooo.``````````````````.
``````````````````.+++++++++++/////////////////////////++++++++++++ooooooooooooo-```````````````````
```````````````````-++++++++++//////////////////////////++++++++++++oooooooooooo/```````````````````
````````````````````/++++//++//////////////////////////////://++/-++oooooooooooo:```````````````````
````````````````````-/+//////////////////////////////////:-.`../..++oooooooooooo-```````````````````
`````````````````````//+///////////::::::::::://///////////-.`````/++ooooooooooo:```````````````````
``````````````````  `:////////:-.````````````.://////////+++///:-``-://+oooooooo:```````````````````
``````````````````   -/////:.``            `-////////////+++++:-``````:+oooooooo-```````````````````
```````````````````  :++/:``             `-//////////////++/:.````````.+oooooooo.```````````````````
```````````````````` .++/.              .:////////////////-``   ```````.++ooooo+````````````````````
`````````````````````.++/`            `-///////////////:.`      ````````-+ooooo/````````````````````
`````````````````````.++:            `://////////////:.`         ````````/++ooo:````````````````````
`````````````````````.++-           `://///////////-.`            ```````-+++oo-````````````````````
`````````````````````-++.          `/////////////:`               ```````.+++oo.````````````````````
`````````````````````:++.         `:////////////.`  ````           ```````+++oo.````````````````````
`````````````````````/o+.``       `--:////////:``.--.````````      ```````++++o-````````````````````
`````````````````````/oo.```  `...:-::.-://///-://-``--:::://:-.` ````````++++o:````````````````````
`````````````````````/oo-`````.-``-.-:```://////-` `.`````--:/:::. ``````.++++o-````````````````````
`````````````````````:oo:``````---.--.-:://///:`      `````----:-` ``````-+++++`````````````````````
`````````````````````:oo+```````:++/:-://////-`         ``...-.``  ``````/+++++.````````````````````
``````````````````````:+o-`````:+/-``-//////.                     ```````+++++/`````````````````````
```````````````````````:+/````-:.` `-++++//.                      ``````.//+/+:`````````````````````
````````````````````````.+:````````-+++++:`                       `````````.::``````````````````````
`````````````````````````.:.``````.++++/-`                     `````````````/.``````````````````````
```````````````````````````:``````/+++/.   ..    .:.       ````````````````:/```````````````````````
```````````````````````````/`````.+++:`    ``    ```    `````````````````.:+-```````````````````````
```````````````````````````/-````/++-```             ````````````````-//++++````````````````````````
```````````````````````````/-````+o:````           `````````````````.++++++/````````````````````````
```````````````````````````/:```.++```````.--.``..``````````````````/+o++++:````````````````````````
```````````````````````````//```.o:````.://///:::/:::-.````````````-+++++++/````````````````````````
```````````````````````````+o-``-o-````..``.......````````````````-/+ooooo++````````````````````````
``````````````````````````-oo+.`:o.`````....`````````````````````::.+ooooo++.```````````````````````
`````````````````````````.+ooo+.:+.`````````......`````````````.:-``+ooooo+:-```````````````````````
`````````````````````````/ooooo-/+````````````````````````````--```.+oooooo/````````````````````````
````````````````````````/oooooo./+`````````````````````````````````.oooooo/+````````````````````````
```````````````````````:ooo++o+`/+`````````````````````````````````.oooo+/:`````````````````````````
``````````````````````.:+/:-//-`++`````````````````````````````````.oooo-`.`````````````````````````
....````````````````````````.```+/``````````````````````````````````+oo:````````````````````````````
.....``````````````````````````.+/``````````````````````````````````:+-`````````````````````````````
......`````````````````````````.+:````````````````````````````````````````````````````````````````..
.........``````````````````````-+:``````````````````````````````````````````````````````````````....
...........````````````````````-o-`````````````````````````````````````````````````````````````.....
.............``````````````````:o-```````````````````````````````````````````````````````````.......
...............````````````````:o-`````````````````````````````````````````````````````````.........
................```````````````/o.```````````````````````````````````````````````````````...........
....................``..```````/+.``````````````````````````````````````````````````.`..............
...........................````:/``````````````````````````````````````.``..........................
.............................`.//````````````````````````````````````...............................
----..........................`..``````````````````````````````.....................................
`````````````````````````````````````````````````````````````````

## Can you hear me, Major Tom?

Push notifications server for bitcoin wallets. Processes blocks & mempool in search of subscribed onchain addresses.
Built with typescript, expressjs, mariadb & openapi.

In memory of David Bowie

### Installation

```shell script
npm install -g dtsgenerator
dtsgen openapi.yaml > src/openapi/api.ts
npm i
npm start
npm run worker-blockprocessor
npm run worker-processmempool
npm run worker-sender
```

Works well on Heroku (you'll need `JawsDB Maria` addon)

### Environment variables

Set them as env variables or put them into `.env` file in project root dir.

- `JAWSDB_MARIA_URL` for example `mysql://username:password@host:port/database`
- `FCM_SERVER_KEY` hex encoded
- `APNS_PEM` hex encoded
- `BITCOIN_RPC` for example `http://username:password@host:8332`

### License

MIT