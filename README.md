# reshapely
Library for data transformation and mashups

Data can be reshaped either as JavaScript/TypeScript or as JSON.  The advantage of JavaScript is that functions can be used to dynamically resolve mappings at runtime, and the advantage of JSON is that the mappings and schemas can be done completely dynamically.

To reshape data, start by defining the shape of the output data you want, and then specifying the JSONPath that property should be mapped from:

```
$..book[0][category,author]
```

<https://github.com/JSONPath-Plus/JSONPath>

## Credits

It takes a lot of inspiration from [Select Transform](https://selecttransform.github.io/site/)
