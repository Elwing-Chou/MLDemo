# MLDemo

## 解壓縮檔案

```python
import zipfile
f = zipfile.ZipFile("regression.zip")
f.extractall("train")
```

## 函式進階

3可以, print就可以

```python
a = print
a(3)
```

讓回傳答案是一個流程

```python
def test():
    return print
test()("hello")
```

## Model使用方式是這樣

```python
Model(inputs=張量, outpus=張量)
```

```python
# 回傳值是一個函式
張量2 = Dense(256, activation="relu)(張量1)
張量3 = Dense(10, activation="softmax")(張量2)
mlp = Model(inputs=張量1, outputs=張量3)
```

## Lambda無名函式

只要用一兩次, 裡面要做的事情又是一兩行就可以搞定的

```python
def test(func):
    print(func(3))
def a(n):
    return 2 * n
# 這兩行是一模一樣的意思
test(a)
test(lambda n:2 * n)

```

