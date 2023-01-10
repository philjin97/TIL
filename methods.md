# Methods
<br/>

## Sequence - String
<br/>

#### Searching/ Checking 
##### *s.find(x)* -> if: returns first index of x, else: -1
##### *s.index(x)* -> if: returns first index of x, else: error
##### *s.isalpha()* -> if alphabet: True, else: false
##### *s.isupper()* -> if uppercase: True, else: false
##### *s.islower()* -> if lowercase: True, else: false
##### *s.istitle()* -> if title: True, else: false
<br/>

#### Changing 
##### *s.replace(old, new[,count])* -> returns string with the new letter in place of the old letter.
##### *s.strip([chars])* -> strips everything other than the determined chars. 
##### *s.split(sep=None, maxsplit=-1)* -> splits a string into a list.
##### *'separator'.join([iterable])* -> joins the separator and the iterable values into a string. 
##### *s.capitalize()* -> capitalizes the first letter and everything else lower.
##### *s.title()* -> capitalizes first letter of each word. 
##### *s.upper()* -> capitalizes every letter.
##### *s.lower* -> lowercase every letter.
##### *s.swapcase* -> swaps the case of each letter. 
<br/>

## Sequence - List
<br/>

##### *L.append(x)* -> adds new component x at right. 
##### *L.insert(i, x)* -> inserts x at index[i].
##### *L.remove(x)* -> removes first x from left. 
##### *L.pop()* -> returns and removes first item from right.
##### *L.pop(i)* -> returns and removes item at index(i). 
##### *L.extend(m)* -> adds list m to list L at the right.
##### *L.index(x, start, end* -> returns index of first x from the left. 
##### *L.reverse()* -> reverses the list.
##### *L.sort()* -> sorts the list in order. 
##### *L.count(x)* -> returns the number of x in the list.


## Collection - Set
<br/>

##### *s.copy()* -> returns copy of the set.
##### *s.add(x)* -> adds item x.
##### *s.pop(x)* -> returns and deletes a random item from the set. if empty set -> keyerror.
##### *s.remove(x)* -> deletes item x from the set. if empty set -> keyerror.
##### *s.discard(x)* -> if item x in the set, deletes x. 
##### *s.update(t)* -> adds items from t that doesn't exist on s. 
##### *s.clear()* -> deletes all items.
##### *s.isdisjoint(t)* -> s and t have completely different items, returns True. 
##### *s.issubset(t)* -> if s contains all items t has, and has more, returns True.
##### *s.issuperset(t)* -> if t contains all items s has, and has more, returns True.
<br/>

## Collection - Dictionary
<br/>

##### *d.clear()* -> deletes all items. 
##### *d.keys()* -> returns all keys of d. 
##### *d.values()* -> returns all values of d. 
##### *d.items()* -> returns all key-value pairs of d. 
##### *d.get(k)* -> returns value of k, else: None. 
##### *d.get(k, v)* -> returns value of k, else: returns v.
##### *d.pop(k)* -> returns value of k and deletes k item, else: keyerror. 
##### *d.pop(k, v)* -> returns value of k and deletes k item, else: returns v. 
##### *d.update([other])* -> updates the value in the dictionary given by other. 
