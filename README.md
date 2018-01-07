# JS Obfuscator
Converts the JavaScript source code into obfuscated.

It uses only 10 different characters (`!+/()[]{},`) to write.

And it supports Chrome, IE, and other browsers.

## Code
``` python
code = 'alert("Hello, World!")'
code = obfuscate(code)
print(code)
```

## Result
```
[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]]+([][[]]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()({})[+[]]+(!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]))+(!![]+[])[+[]]+(!![]+[])[+!![]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+(+(+!![]+(!![]+[])[!![]+!![]+!![]]+(+!![])+(+[])+(+[])+(+[]))+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[+[]]+([]+[])[(![]+[])[+[]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(!![]+[])[+[]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+(!![]+[])[+!![]]]()[(+!![]+[])+(!![]+!![])]+([]+[])[(![]+[])[+[]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(!![]+[])[+[]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+(!![]+[])[+!![]]]()[(+!![]+[])+(!![]+!![])])()[!![]+!![]+!![]+!![]+!![]])()[(![]+[])[+[]]+(!![]+[])[+!![]]+({}+[])[+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+(+(+!![]+(!![]+[])[!![]+!![]+!![]]+(+!![])+(+[])+(+[])+(+[]))+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[+[]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(+[]+[]))()[!![]+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()((+!![]+[])[(![]+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]]]())[!![]+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[+[]]+(![]+[])[+!![]]+(!![]+[])[+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()((+!![]+[])[(![]+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]]]())[!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[!![]+!![]]+(!![]+[])[!![]+!![]+!![]]]((!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(+!![]+[]),(+!![]+[])+(+!![]+[])+(!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+!![]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+!![]+[])+(+[]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+[]),(+!![]+[])+(+[]+[])+(+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+!![]+[])+(+!![]+[]),(!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+[]),(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+!![]+[])+(+!![]+[]),(+!![]+[])+(+!![]+[])+(!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(+[]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+!![]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+!![]+[])+(+!![]+[])))()
```
