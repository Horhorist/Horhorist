<img src="https://i.hizliresim.com/qsgdd1b.gif" width="250" align="right"> 

💻 **Things I love**
- Python 
- Backend Development 
- Machine Learning 

```bash
> nmap -Pn -sS horhorist.netlify.com
```



```python
from dataclasses import dataclass

class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)

class Social(metaclass=Meta):
    spotify     : str = "horhorik"
    instagram   : str = "iamhornik"
    
    class Bio(metaclass=Meta):
    name        : str = "horhorist"
    designation : str = "Hacker, software engineer, ai dev."
    company     : str = "horhorist"
    age         : str = "17"
    website     : str = "horhorist.netlify.com"
    
class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Go", "JavaScript", "Java", "C++", "c#")
    databases   : Tuple[str, ...] = ("MySQL", "Mongo")
    ongoing     : Tuple[str, ...] = ("Django")
```



       

