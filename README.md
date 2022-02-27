# gdf
GDF (Game Data Format) is a data format that is easy to implement and can be used to store basic data

## gdf-1 Standard

### Example
```
@ This is a comment!!

"Hello! This is a string";
f12.02; @ A float!
i2000;  @ an integer
l50;    @ a long
u25;    @ an unsigned integer

[;      @ array, we can represent different data types like this. for example a color
u225;
u225;
u225;
u225;
];

```

## Remarks
 - To speed up parsing, its recommended to go to the next line when a "@" or a ";" is hit
 - This standard recommends the `i` type to be translated to a 32-bit integer.
