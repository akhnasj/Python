# Python
Python is a versatile, high-level programming language known for its readability and ease of use. It’s widely used in various fields, including web development, data analysis, artificial intelligence, scientific computing, and more.

## Key Features of Python
- ***Readable and Maintainable Code*** :  Python’s syntax is designed to be readable and straightforward, making it easier to write and maintain code.

- ***Extensive Standard Library***: Python comes with a rich standard library that supports many common programming tasks, such as file I/O, system calls, and even web browsers.

- ***Dynamic Typing***: Python is dynamically typed, meaning you don’t need to declare the type of a variable when you create one.
- ***Interpreted Language***: Python is an interpreted language, which means the code is executed line by line, making debugging easier.
- ***Cross-Platform***: Python runs on various platforms, including Windows, macOS, and Linux.

## Popular Libraries and Frameworks
**Web Development**: Django, Flask\
**Data Analysis**: Pandas, NumPy\
**Machine Learning**: TensorFlow, Scikit-learn\
**GUI Development**: Tkinter, PyQt

# 1. Variables and Datatypes

### i) Text Type
**str** : Used for text (strings).

    text = "Hello, World!"

### ii) Numeric Types
**int** : Integer numbers.\
**float** : Floating-point numbers.\
**complex** : Complex numbers.

    integer = 42
    floating = 3.14
    complex_num = 1 + 2j

### iii) Sequence Types
**list** : Ordered collection of items.\
**tuple** : Ordered, immutable collection of items.\
**range** : Represents a sequence of numbers.

    list_example = [1, 2, 3]
    tuple_example = (1, 2, 3)
    range_example = range(5)

### iv) Mapping Type
**dict** : Key-value pairs.

    dict_example = {"name": "Alice", "age": 30}
### v) Set Types
**set** : Unordered collection of unique items.\
**frozenset** : Immutable version of a set.

    set_example = {1, 2, 3}
    frozenset_example = frozenset([1, 2, 3])

### vi) Boolean Type
**bool** : Represents True or False.

    boolean = True

### vii) Binary Types
**bytes** : Immutable sequence of bytes.\
**bytearray** : Mutable sequence of bytes.\
**memoryview** : Allows access to the internal data of an object that supports the buffer protocol.

    bytes_example = b"Hello"
    bytearray_example = bytearray(5)
    memoryview_example = memoryview(bytes(5))

### viii) None Type
**NoneType** : Represents the absence of a value or a null value.

    none_example = None

# 2. Arithmetic Operators

- **Addition (+)** : Adds two numbers.

        result = 10 + 5  
   

- **Subtraction (-)** : Subtracts the second number from the first.

        result = 10 - 5

- **Multiplication (*)** : Multiplies two numbers.

        result = 10 * 5 

- **Division (/)** : Divides the first number by the second.

        result = 10 / 5  
        
- **Floor Division (//)** : Divides the first number by the second and returns the largest integer less than or equal to the result.

        result = 10 // 3 

- **Modulus (%)** : Returns the remainder of the division.

        result = 10 % 3  

- **Exponentiation (\**)** : Raises the first number to the power of the second.

        result = 2 ** 3  
    
## Additional Operators
- **Assignment Operators** : =, +=, -=, *=, /=, etc.
```py
    a = 5
    a /= 2
    a &= 3
    a >>= 2
```

- **Comparison Operators** : ==, !=, >, <, >=, <=

```py
    print(a == b) 
    print(a > b)
```

- **Logical Operators** : and, or, not
```py
    print(x and y)            
    print(x or y)   
    print(not x) 
```

- **Bitwise Operators** : &, | , ^, ~, <<, >>
```py
     result = a & b             # AND
     result = a | b             # OR
     result = a ^ b             # XOR
     result = ~a                # NOT
     result = a << 2            # Bitwise Left Shift
```

- **Boolean Functions** : Converts a value to boolean
    
```py
    print(bool(1))              # True
    print(bool(0))              # False
    print(bool(""))             # False
    print(bool("Hello"))        # True
```