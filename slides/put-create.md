#  PUT Create

```
db.put(doc, [docId], [docRev], [options], [callback]);

var doc = {
  _id: "devtalkscluj",
  event: "DevTalks Cluj",
  type: "conference",
  date: "2017-05-17"
}
db.put(doc, function(err, response) {
  if (err) { return console.log(err); }
  // handle response
});
```
