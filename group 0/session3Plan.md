# Session 3

### Starting conversation
- ana msh bakeep attendance we score zy el hr, temshy bel 7ob azraf
- fi nas 3amalo el ctd we nas la, ely hay2asar fel shoghl ba3d kda  hayban 3aleih unless howa gamed yeb2a tamam
- ely katabo comments 3ash nas gamda walahy


### CTD 1
```python
values = [] 
while True:
    x = input("Enter value: ")
    if x != 'q':
        values.append(int(x))
    else:
        break
print(f"Max: {max(values)} and Min: {min(values)}")
```
---
### CTD 2
```python
friends1 = []
friends2 = []
while True:
    name = input("User 1: ")
    if name != 'q':
        friends1.append(name)
    else:
        break


while True:
    name = input("User 2: ")
    if name != 'q':
        friends2.append(name)
    else:
        break
```
akid kolo 3amal copy past hena, should have used functions instead like so:
- we use functions to reuse code
- not to structure code
```python
def getNames():
    names
    while True:
        name = input("User 2: ")
        if name != 'q':
            names.append(name)
        else:
            break
    return names

friends1 = getNames()
friends2 = getNames()

```
- getting common elements 
```python
results = [name for name in friends1 if name in friends2]
```
or
```python
results = set(a) & set(b)
```
or
```python
results = set(a).intersection(set(b))
```
```python
print("Mutual Friends:", results)
```
