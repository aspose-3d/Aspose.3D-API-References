---
title: "PushConstant"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Утилита для передачи данных в шейдер через push‑constant.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор PushConstant |

 **Result:**



---


### write{#write}

| Имя | Описание |
| --- | --- |
| write(mat) | Записать матрицу в константу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| mat | FMatrix4 | Матрица для записи |

 **Result:**



---


### write{#write}

| Имя | Описание |
| --- | --- |
| write(n) | Записать целое значение в константу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### write{#write}

| Имя | Описание |
| --- | --- |
| write(f) | Записать значение float в константу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### write{#write}

| Имя | Описание |
| --- | --- |
| write(vec) | Записать 4‑компонентный вектор в константу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Имя | Описание |
| --- | --- |
| write(vec) | Записать 3‑компонентный вектор в константу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Имя | Описание |
| --- | --- |
| write(x, y, z, w) | Записать 4‑компонентный вектор в константу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### commit{#commit}

| Имя | Описание |
| --- | --- |
| commit(stage, commandList) | Зафиксировать подготовленные данные в графическом конвейере. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| stage | Number | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



