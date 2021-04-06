```python
from nltk.stem.porter import PorterStemmer
from nltk.tokenize import word_tokenize
```


```python
ps=PorterStemmer()
```


```python
words=["Program","programs","programmer","programing","programers"]
```


```python
for w in words:
    print(w," : ",ps.stem(w))
```

    Program  :  program
    programs  :  program
    programmer  :  programm
    programing  :  program
    programers  :  program
    


```python
#stemming words from sentences
```


```python
from nltk.stem.porter import PorterStemmer
from nltk.tokenize import word_tokenize
```


```python
ps=PorterStemmer()
```


```python
sentence="Programers program with programing languages"
words=word_tokenize(sentence)
```


```python
for w in words:
    print(w," : ",ps.stem(w))
```

    Programers  :  program
    program  :  program
    with  :  with
    programing  :  program
    languages  :  languag
    


```python

```
