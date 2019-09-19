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
