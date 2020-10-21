# dailysasin
#### Space edition

Surowy json: https://raw.githubusercontent.com/FireBite/dailysasin/master/dailysasin.json

## Example
```
$.getJSON("https://raw.githubusercontent.com/FireBite/dailysasin/master/dailysasin.json", (data) => {
  console.log('dailysasin: ' + data.facts[Math.floor(Math.random() * data.facts.length)]);
  console.log('dailysasin: more at https://github.com/FireBite/dailysasin');
});
```


##### PS: Jacek Sasin przewalił 70 milionów złotych na wybory korespondencyjne i nie poniósł żadnych konsekwencji
