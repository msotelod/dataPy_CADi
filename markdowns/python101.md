# Python 101

##  Introduction


<hr>

##  First Steps

### Hello World!

```python
print("Hello World!")
```

### Functions

```python
def lstToStr(inList):
  converted = ",".join(str(e) for e in inList)
  return "[" + converted + "]"
```

### Types

```python
num = 10
strg = "Hello World!"
num = "test"
```
<hr>

##  Mutability



##### Mutable


######  Lists

```python
# Lists
lstA = [1, 2, 3, 4]
lstA[0] = 5
print(",".join(str(e) for e in lstA))
```

```python
lstB = lstA
lstA[0] = -1

print(
  "A: [" + ",".join(str(e) for e in lstA) + "] \n" +
  "B: [" + ",".join(str(e) for e in lstA) + "]"
)
```

##### Immutable

```python
# Strings
strg = "Strings are immutable"
strg[0] = "Z"

# Tuples
tup = (1,2)
```