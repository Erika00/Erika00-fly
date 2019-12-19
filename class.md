```
class Shoes:
    kind = ''
    def __init__(self, name):
        self.name = name
    def Heel(self):
        return '...'
    def Length(self):
        return'...'
class A(Shoes):
    def Heel(self):
        return'low'
    def Length(self):
        return'37'
class B(Shoes):
    def Heel(self):
        return'high'
    def Length(self):
        return'36'
a = A ('slippers')   
b = B ('boots')
print(a.name, a.Length(), a.Heel())
print(b.name, b.Length(), b.Heel())
```

```
slippers 37 low
boots 36 high
```
