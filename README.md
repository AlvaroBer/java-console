# Java Console class v 0.1 
The purpose of this class is to help to print default Java's objects in the console, for example, the class can print HashMap and ArrayList objects.

These are the object types that, at the moment, are available.

* ArrayList
* HashMap
* Array

Warning: the class doesn't work with primitive types like `int`


<br />

## Main examples
Some few usage examples of log method.

### log method

Code
```
Console console = new Console();

HashMap<String, Integer> map = new HashMap<String, Integer>();

map.put("key1", 1);
map.put("key2", 120);
map.put("key3", 15);

console.log(map);
```

Result
```
{key3: 15, key2: 120, key1: 1}
```

<br />

Code
```
Console console = new Console();

List<String> list = new ArrayList<String>();

list.add("element1");
list.add("element2");
list.add("element3");

console.log(list);
```

Result
```
{element1, element2, element3}
```

<br />

Code
```
Console console = new Console();

Integer[] list = {1,2,3,4,5,6,7};

console.log(list);
```

Result
```
[1, 2, 3, 4, 5, 6, 7]
```

<br />

### element method

Code
```
Console console = new Console();

HashMap<String, Integer> map = new HashMap<String, Integer>();

map.put("key1", 1);
map.put("key2", 120);
map.put("key3", 15);

console.log(map);
```

Result
```
{key3: 15, key2: 120, key1: 1}
```

<br />

![alt tag](http://es.creativecommons.org/blog/wp-content/uploads/2013/04/by_petit.png)
