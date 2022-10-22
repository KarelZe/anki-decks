# Note
```
guid: z=]f//@9~O
notetype: Basic-d7a3e-4ce08
```

### Tags
```
12_Vektorverarbeitung
```

## Front
Wie funktioniert ein <b>Vektor-Mask-Register</b> für <b>bedingt
ausgeführten Anweisungen</b>?

## Back
Jede ausgeführte Vektorinstruktion arbeitet nur auf den Vektorelementen, deren Einträge eine 1 haben. Die Einträge im Zielvektorregister, die eine 0 im entsprechenden Feld des Vektor-Mask-Registers haben, werden nicht verändert.
