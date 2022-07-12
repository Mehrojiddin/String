# String
The String object is used to represent and construct a sequence of characters.

# String Methods
Primitive values, like "John Doe", cannot have properties or methods (because they are not objects).

But with JavaScript, methods and properties are also available to primitive values, because JavaScript treats primitive values as objects when executing methods and properties.

## JavaScript String Length
The length property returns the length of a string:

## Extracting String Parts
There are 3 methods for extracting a part of a string:

slice(start, end)
substring(start, end)
substr(start, length)

### JavaScript String slice()
slice() extracts a part of a string and returns the extracted part in a new string.

The method takes 2 parameters: the start position, and the end position (end not included).
### JavaScript String substring()
substring() is similar to slice().

The difference is that start and end values less than 0 are treated as 0 in substring().

### JavaScript String substr()
substr() is similar to slice().

The difference is that the second parameter specifies the length of the extracted part.

### Replacing String Content

The replace() method replaces a specified value with another value in a string:


### JavaScript String toUpperCase()

### JavaScript String toLowerCase()

### JavaScript String concat()
concat() joins two or more strings:

### JavaScript String trim()
The trim() method removes whitespace from both sides of a string:

