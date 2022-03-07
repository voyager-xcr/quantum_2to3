运行 `\bin\LabRAD-v1.1.3.exe`



然后在`\lib\` 目录用python（终端可以用ipython）运行以下测试

```python
import labrad
cxn = labrad.connect()
```



输入 `cxn` 后正常会显示

```
In [4]: cxn
Out[4]:
LabRAD Client: 'Python Client (zee)' on localhost:None

Available servers:
    manager
    registry
```

