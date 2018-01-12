## Regex

* Regex that matches: ```antelope  && antelopes```

```
/antelopes?/g
```
* Regex that matches: ``` goat && moat !boat```

```
/[g|m]oat/g
```

* Regex that matches dates in YYYY-MM-DD format.
` Method 1`
```
/\d{4}-\d{2}-\d{2}/g
```
` Method 2`
```
/\d{4}-(1[0-2]|[1-9])-\d{2}/g
```


## State Machines

* Draw a state machine that corresponds to the following regex:

      ab*c+d?[ef]

![a b* c+ d? [ef]](https://raw.githubusercontent.com/Spongenuity/Sprint-Challenge--Theory-Algorithms/master/theory/img/abc.png)



* A lion can be sleeping, eating, hunting, or preening. Draw a state machine diagram for the lion

![Lion](https://raw.githubusercontent.com/Spongenuity/Sprint-Challenge--Theory-Algorithms/master/theory/img/Lion.png)