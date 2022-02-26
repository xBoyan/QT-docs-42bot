# Quicktask documentation for 42bot

Here's quick documentation for cookgroups which will allow them add 42bot's quicktasks to their monitors.
## General quicktask format
`http://127.0.0.1:2424/quicktask?site={siteName}&url={url/pid}`
## Here's the list of what sites and which "urls" should be used, followed by an example

* ### AboutYou
  * site - `aboutyou`
  * url - `generalPid` or `generalPid.sizePid` or `generalPid.sizePid;sizePid;sizePid`
  * example - `http://127.0.0.1:2424/quicktask?site=aboutyou&url=7789288.49481241;49481242;49481243;49481244;49481245;49481246`

* ### Ambush
  * site - `ambush;drops` or `ambush;www`
  * url - `pid`
  * example - `http://127.0.0.1:2424/quicktask?site=ambush;drops&url=123456`

* ### BSTN
  * site - `bstn`
  * url - `url`
  * example - `http://127.0.0.1:2424/quicktask?site=bstn&url=https://www.bstn.com/eu_en/r/jordan-air-jordan-11-retro-cool-grey-ct8012-005-0263045`
  
* ### Footasylum
  * site - `footasylum`
  * url - `generalPid` or `sizePid` or `sizePid;sizePid;sizePid`
  * example - `http://127.0.0.1:2424/quicktask?site=footasylum&url=405190601;405190602`

* ### Footshop
  * site - `footshop`
  * url - `url`
  * example - `http://127.0.0.1:2424/quicktask?site=footshop&url=https://www.footshop.pl/pl/buty-damskie/153142-nike-w-air-force-1-low-premium-summit-white-summit-white-sea-glass.html`

* ### KITH
  * site - `kith`
  * url - `url`
  * example - `http://127.0.0.1:2424/quicktask?site=kith&url=https://eu.kith.com/products/jbdd9335-641`

* ### Mesh
  * site - `store;region;fe/be` -> `size;fr;be`
  * url - `generalPid` or `generalPid.sizePid`
  * example - `http://127.0.0.1:2424/quicktask?site=size;fr;be&url=457062_sizefr.002255419`

* ### Off-White
  * site - `offwhite;drops` or `offwhite;www`
  * url - `pid`
  * example - `http://127.0.0.1:2424/quicktask?site=offwhite;drops&url=123456`

* ### Office
  * site - `office`
  * url - `generalPid` or `url`
  * example - `http://127.0.0.1:2424/quicktask?site=office&url=4382409196`

* ### Offspring
  * site - `offspring`
  * url - `generalPid` or `url`
  * example - `http://127.0.0.1:2424/quicktask?site=offspring&url=4470381040`

* ### Sizeer
  * site - `sizeer`
  * url - `url`
  * example - `http://127.0.0.1:2424/quicktask?site=sizeer&url=https://sklep.sizeer.com/nike-dunk-low-og-damskie-sneakersy-zolty-dm9467-700`

* ### SNS
  * site - `sns`
  * url - `generalPid` or `generalPid.sizePid` or `generalPid.sizePid;sizePid;sizePid`
  * example - `http://127.0.0.1:2424/quicktask?site=sns&url=52435`

* ### Szopex [WSS and SKstore]
  * site - `szopex` or `wss` or `sk`
  * url - `url`
  * example - `http://127.0.0.1:2424/quicktask?site=szopex&url=https://warsawsneakerstore.com/nike-dunk-low-retro-dj6188-400.html`

* ### Titolo
  * site - `titolo`
  * url - `url`
  * example - `http://127.0.0.1:2424/quicktask?site=titolo&url=https://www.titoloshop.com/eu_en/wmns-air-jordan-1-low-se-dd9337-106.html`

* ### Vitkac
  * site - `vitkac`
  * url - `sizePid`
  * example - `http://127.0.0.1:2424/quicktask?site=vitkac&url=1713388`

* ### Zalando
  * site - `zalando`
  * url - `sizePid` or `sizePid;sizePid`
  * example - `http://127.0.0.1:2424/quicktask?site=zalando&url=NI111A0ZP-A110055000;NI111A0ZP-A110060000NI111A0ZP-A110065000`
  
