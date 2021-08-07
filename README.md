# Metric Prefixes in JSON	

This was procured from the wikipedia table: https://en.wikipedia.org/wiki/Template:SI_prefixes_(infobox)

For metricArr.json, the prefixes are stored in an array, with each prefix being stored as an object, with keys:
[prefix (str), symbol (str), exp (int), wordShort (str), wordLong (str), adoption (str)]

for metricObj.json, the prefixes are stored in an object. With they key being the prefix (str), which accesses an object. 
Everything else in that object is the same as metricArr.json.


NOTE: exp is in base10
