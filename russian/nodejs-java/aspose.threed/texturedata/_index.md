---
title: "TextureData"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Этот класс содержит необработанные данные и определение формата текстуры.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Конструктор класса TextureData |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| widt | Number | null |
| heigh | Number | null |
| strid | Number | null |
| bytesPerPixe | Number | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Создаёт новый объект TextureData и выделяет данные пикселей. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| widt | Number | null |
| heigh | Number | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2() | Конструктор класса TextureData |

 **Result:**



---


### getData{#getData}

| Имя | Описание |
| --- | --- |
| getData() | Сырые байты данных пикселей |

 **Result:**



---


### getWidth{#getWidth}

| Имя | Описание |
| --- | --- |
| getWidth() | Количество горизонтальных пикселей |

 **Result:**



---


### getHeight{#getHeight}

| Имя | Описание |
| --- | --- |
| getHeight() | Количество вертикальных пикселей |

 **Result:**



---


### getStride{#getStride}

| Имя | Описание |
| --- | --- |
| getStride() | Количество байтов в строке сканирования. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Имя | Описание |
| --- | --- |
| getBytesPerPixel() | Количество байтов в пикселе |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Имя | Описание |
| --- | --- |
| getPixelFormat() | Формат пикселя. Значение свойства — целочисленная константа PixelFormat. |

 **Result:**



---


### fromFile{#fromFile}

| Имя | Описание |
| --- | --- |
| fromFile(fileName) | Загрузить текстуру из файла |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| Имя | Описание |
| --- | --- |
| save(fileName) | Сохранить данные текстуры в файл изображения |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла, в котором будет сохранено изображение. |

 **Result:**
TextureData


---


### save{#save}

| Имя | Описание |
| --- | --- |
| save(fileName, format) | Сохранить данные текстуры в файл изображения |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла, в котором будет сохранено изображение. |
| format | String | Формат изображения выходного файла. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Имя | Описание |
| --- | --- |
| mapPixels(mapMode) | Отобразить все пиксели для чтения/записи |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Имя | Описание |
| --- | --- |
| mapPixels(mapMode, format) | Отобразить все пиксели для чтения/записи в заданном формате пикселей |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Имя | Описание |
| --- | --- |
| mapPixels(rect, mapMode, format) | Отобразить пиксели, указанные прямоугольником rect, для чтения/записи в заданном формате пикселей |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rect | Rect | Область пикселей для доступа |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Имя | Описание |
| --- | --- |
| transformPixelFormat(pixelFormat) | Преобразовать расположение пикселя в новый формат пикселей. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



