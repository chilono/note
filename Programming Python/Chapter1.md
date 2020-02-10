# Chapter1

## 函数

### zip

连接两段列表

```python
>>> names = ['name', 'age', 'pay', 'job']
>>> values = ['Sue Jones', 45, 40000, 'hdw']
>>> list(zip(names, values))
[('name', 'Sue Jones'), ('age', 45), ('pay', 40000), ('job', 'hdw')]
```

### pprint

打印函数，格式很人性化

所属模块: pprint

```python
>>> import pprint
>>> bob = dict(name='Bob Smith', age=42, pay=30000, job='software')
>>> remu = {'name':'博丽 灵梦', 'age':17, 'pay':10, 'job':'巫女'}
>>> poi = {'name':'夕立', 'age':16, 'pay':800, 'job':'舰娘'}
>>> peopel = [bob, remu, poi]
>>> pprint.pprint(peopel)
[{'age': 42, 'job': 'software', 'name': 'Bob Smith', 'pay': 30000},
 {'age': 17, 'job': '巫女', 'name': '博丽 灵梦', 'pay': 10},
 {'age': 16, 'job': '舰娘', 'name': '夕立', 'pay': 800}]
```



### Pickle模块

```python
# 导入模块
import pickle

# 将要对象db写入dbfile
pickle.dump(db, dbfile)

# 读取dbfile文件写入对象db
db = pickle.load(dbfile)
```



### getattr

获取对象的属性

```python
attr = getattr(对象, 属性名)
```





































