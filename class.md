```
class Shoes:
    kind = ''
    def __init__(self, name):
        self.name = name
    def Heel(self):
        return '...'
    def length(self):
        return'...'
class white(Shoes):
    def Heel(self):
        return'low'
    def length(self):
        return'37'
class black(Shoes):
    def heel(self):
        return'hight'
    def length(self):
        return'36'
w = white('slippers')
b = black('boots')
print('w.name, w.heel(), w.length()')
print('b.name, b.heel(), b.length()')

```
```
w.name, w.heel(), w.length()
b.name, b.heel(), b.length()






```