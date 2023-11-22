
💻 **Things I love**
- Python 
- Backend Development

```python
from dataclasses import dataclass

class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)

class Social(metaclass=Meta):
    spotify     : str = "horhorik"
    instagram   : str = "horhorikk"
    tirsik.net  : str = "horhorik"
    
    class Bio(metaclass=Meta):
    name        : str = "horhorist"
    designation : str = "a student fond of software"
    company     : str = "horhorist"
    age         : str = "17"
    website     : str = "https://www.tirsik.net/niviskar.php?trskvn=1394301618&m=kiye"
    
class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Go", "JavaScript", "ruby", "C++", "ruby on rails")
    databases   : Tuple[str, ...] = ("Mongo")
    ongoing     : Tuple[str, ...] = ("Django")
```



       

