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