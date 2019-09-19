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


