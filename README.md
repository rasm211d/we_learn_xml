# Om XML

```<tag> data </tag> ``` - der kan frit defineres start- og sluttags

```<tag />``` - nogle tags er start- og sluttags i et (empty tag)

```<tag attribut1="x" attribut2="2">``` -  et tag kan have mange attributter

```<foo><bar></bar></foo>``` - tags kan indlejres i hinanden efter behov, disse kaldes child / parent tags

```<?xml version="1.0" encoding="UTF-8"?>``` - kan begynde med declarations, men ikke et krav

```<!-- kommentar -->```  - kommentarer skrives sådan

# Om JSON

Json kan ca. det samme som XML, men er simplere.

**Json består af key-value pairs.**

```{}``` - står for et tøm objekt

```[]``` - står for et tøm array

Et eksempel på et personobjekt: 
```{
  "firstName": "John",
  "lastName": "Smith",
  "isAlive": true,
  "age": 27,
  "address": {
    "streetAddress": "21 2nd Street",
    "city": "New York",
    "state": "NY",
    "postalCode": "10021-3100"
  },
  "phoneNumbers": [
    {
      "type": "home",
      "number": "212 555-1234"
    },
    {
      "type": "office",
      "number": "646 555-4567"
    },
    {
      "type": "mobile",
      "number": "123 456-7890"
    }
  ],
  "children": [],
  "spouse": null
}```

