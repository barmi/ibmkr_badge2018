# device내부의 파일 읽기

다음 catfile()함수를 작성해서, serial로 파일을 읽을 수 있습니다.

``` python
def catfile(fn):
    f = open(fn)
    print(f.read())
    f.close()
```

``` bash
>>> catfile('boot.py')
```
