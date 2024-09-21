# lb_6
21.09.24 

# Используемый код:

1)
```
pm.collectionVariables.set("param", JSON.parse(responseBody).args.name)
```
2)
```
console.log(pm.collectionVariables.get("param"))
```
3)
```
var firstName = pm.collectionVariables.get("param");
pm.collectionVariables.set("param", firstName+" Pinkman");
```
