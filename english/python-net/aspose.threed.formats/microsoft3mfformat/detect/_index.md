﻿---
title: detect method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.threed.formats/microsoft3mfformat/detect/
is_root: false
---

## detect {#str}

Detect the file format from file name, file must be readable so Aspose.3D can detect the file format through file header.


### Returns 


The [`FileFormat`](/3d/python-net/aspose.threed/fileformat) instance of the detected type or null if failed.


```python
def detect(self, file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_name | str | Path to the file to detect file format. |
### Exceptions
| Exception | Description |
| :- | :- |
| IOException | Exception thrown when failed to read data. |



### Example 


```python
from aspose.threed import FileFormat

fmt = FileFormat.detect("input.fbx")
print(f"Input file format: {fmt}")

```


## detect {#io.RawIOBase-str}

Detect the file format from data stream, file name is optional for guessing types that has no magic header.


### Returns 


The [`FileFormat`](/3d/python-net/aspose.threed/fileformat) instance of the detected type or null if failed.


```python
def detect(self, stream, file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | Stream containing data to detect |
| file_name | str | Original file name of the data, used as hint. |
### Exceptions
| Exception | Description |
| :- | :- |
| IOException | Exception thrown when failed to read data. |



### Example 


```python
from aspose.threed import FileFormat
from io import BytesIO
import bytearray

bytes = bytearray(100)
fmt = FileFormat.detect(BytesIO(bytes), "input-file")
print(f"Input data format: {fmt}")

```



### See Also
* module [`aspose.threed.formats`](../../)
* class [`FileFormat`](/3d/python-net/aspose.threed/fileformat)
* class [`Microsoft3MFFormat`](/3d/python-net/aspose.threed.formats/microsoft3mfformat)