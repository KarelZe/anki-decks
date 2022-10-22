# Note
```
guid: l`B9U/eGIk
notetype: Basic-b122e-20a86
```

### Tags
```
3_5_synchronisation
```

## Front
Worin liegt der Unterschied zwischen einem binären Semaphor und einer Schlossvariablen?

## Back
Neben der Syntax im Wesentlichen, dass ein unlock <b>nur</b> von
dem Prozess/Thread durchgeführt werden kann, der die lock-Operation
ausgeführt hat, während diese Beschränkung bei der V-Operation von
Semaphoren <b>nicht</b> gilt.
