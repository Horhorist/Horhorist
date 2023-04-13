<img src="https://i.hizliresim.com/cv6zapa.jpg" width="300" align="right"> 

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
    twitter     : str = "horhorist"
    spotify     : str = "hoihorik"
    instagram   : str = "iamhornik"
    mastodon    : str = "horhorist"
    
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
<p align="left">
  <a href="https://horhorist.netlify.com"></a>
</p>

<iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/3t9jjbZP22SQmRMa4C0puE?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
       

       

