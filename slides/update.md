#  Update

```
db.put(doc, [docId], [docRev], [options], [callback]);

db.get('devtalkscluj', function(err, doc) {
  if (err) { return console.log(err); }
  db.put({
    _id: 'devtalkscluj',
    _rev: doc._rev,
    talk: "No Service",
    status: "In Progress"
  }, function(err, response) {
    if (err) { return console.log(err); }
    // handle response
  });
});
```
