# Python Basics
    - Hello World
    - Variables


```python
print("Hello World")
```

    Hello World
    


```python
a = 10.5
b = 15

print(a)
print(b)
```

    10.5
    15
    


```python
print(type(a))
print(type(b))
```

    <class 'int'>
    <class 'int'>
    


```python
c= "random_string"
print(type(c))
```

    <class 'str'>
    


```python
d = 5 + 3j
print (d)
print(type(d))
```

    (5+3j)
    <class 'complex'>
    


```python
a = 200
```


```python
print(a)
print(type(a))
```

    10.5
    <class 'float'>
    

## Input


```python
name = input("Enter the name of your organisation: ")
print("Hello",end=' ')
print(name)
```

    Enter the name of your organisation: Paul
    Hello Paul
    

## Output (Reading Numbers --> Typecasting)


```python
a= int(input("Enter a Number: "))
print(a)
print(a*a)

print (type(a))
print("The square of the number is " + str(a*a))

```

    Enter a Number: 5
    5
    25
    <class 'int'>
    The square of the number is 25
    

## More about Print function
- format
- end and sep parameter


```python
print("Hello","World","I","Love","Python",sep="+")
```

    Hello+World+I+Love+Python
    


```python
a = 10
b = 20
print(a,end=',')
print(b)
```

    10,20
    


```python
a = "Indians"
b = "Mangoes"
c = "Russians"
d = "Pizza"
```


```python
print("{0} love {1}".format(c,d))
```

    Russians love Pizza
    


```python
a = 10
b = 20

print("You entered %d and %d and %d"%(a,b,b))
```

    You entered 10 and 20 and 20
    


```python

```
