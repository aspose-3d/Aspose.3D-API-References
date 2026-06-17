---
title: "Discreet3dsSaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Параметры сохранения для файла 3DS.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор Discreet3dsSaveOptions |

 **Result:**



---


### getExportLight{#getExportLight}

| Имя | Описание |
| --- | --- |
| getExportLight() | Получает или задает, экспортировать ли все источники света в сцене. |

 **Result:**



---


### setExportLight{#setExportLight}

| Имя | Описание |
| --- | --- |
| setExportLight(value) | Получает или задает, экспортировать ли все источники света в сцене. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Имя | Описание |
| --- | --- |
| getExportCamera() | Получает или задает, экспортировать ли все камеры в сцене. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Имя | Описание |
| --- | --- |
| setExportCamera(value) | Получает или задает, экспортировать ли все камеры в сцене. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Имя | Описание |
| --- | --- |
| getDuplicatedNameSeparator() | Разделитель между именем объекта и счётчиком дубликатов, значение по умолчанию — "_". Когда сцена содержит объекты с одинаковыми именами, экспортёр Aspose.3D 3DS создаст другое имя для объекта. Например, есть два узла с именем "Box", первый узел будет иметь имя "Box", а второй получит новое имя "Box_2" при использовании конфигурации по умолчанию. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Имя | Описание |
| --- | --- |
| setDuplicatedNameSeparator(value) | Разделитель между именем объекта и счётчиком дубликатов, значение по умолчанию — "_". Когда сцена содержит объекты с одинаковыми именами, экспортёр Aspose.3D 3DS создаст другое имя для объекта. Например, есть два узла с именем "Box", первый узел будет иметь имя "Box", а второй получит новое имя "Box_2" при использовании конфигурации по умолчанию. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Имя | Описание |
| --- | --- |
| getDuplicatedNameCounterBase() | Счётчик, используемый при генерации нового имени для дублированных имен, значение по умолчанию — 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Имя | Описание |
| --- | --- |
| setDuplicatedNameCounterBase(value) | Счётчик, используемый при генерации нового имени для дублированных имен, значение по умолчанию — 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Имя | Описание |
| --- | --- |
| getDuplicatedNameCounterFormat() | Формат дублированного счётчика, значение по умолчанию — пустая строка. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Имя | Описание |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Формат дублированного счётчика, значение по умолчанию — пустая строка. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Имя | Описание |
| --- | --- |
| getMasterScale() | Получает или задает основной масштаб, используемый при экспорте. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Имя | Описание |
| --- | --- |
| setMasterScale(value) | Получает или задает основной масштаб, используемый при экспорте. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Имя | Описание |
| --- | --- |
| getGammaCorrectedColor() | Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута. Установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно; в противном случае Aspose.3D попробует использовать оригинальный цвет. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Имя | Описание |
| --- | --- |
| setGammaCorrectedColor(value) | Файл 3ds может содержать оригинальный цвет и цвет с гамма‑коррекцией для одного и того же атрибута. Установка этого параметра в true заставит использовать цвет с гамма‑коррекцией, если это возможно; в противном случае Aspose.3D попробует использовать оригинальный цвет. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| getFlipCoordinateSystem() | Получает или задает систему координат отражения контрольных точек/нормалей при импорте/экспорте. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Имя | Описание |
| --- | --- |
| setFlipCoordinateSystem(value) | Получает или задает систему координат отражения контрольных точек/нормалей при импорте/экспорте. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Имя | Описание |
| --- | --- |
| getHighPreciseColor() | Если это true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зеленого/синего будет представлять 32‑битный float. В противном случае сгенерированный файл будет использовать 24‑битный цвет, каждый канал — 8‑битный байт. Значение по умолчанию — false, потому что не все приложения поддерживают высокоточный цвет. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Имя | Описание |
| --- | --- |
| setHighPreciseColor(value) | Если это true, сгенерированный файл 3ds будет использовать высокоточный цвет, то есть каждый канал красного/зеленого/синего будет представлять 32‑битный float. В противном случае сгенерированный файл будет использовать 24‑битный цвет, каждый канал — 8‑битный байт. Значение по умолчанию — false, потому что не все приложения поддерживают высокоточный цвет. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Имя | Описание |
| --- | --- |
| getExportTextures() | Попробовать скопировать текстуры, используемые в сцене, в выходной каталог. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Имя | Описание |
| --- | --- |
| setExportTextures(value) | Попробовать скопировать текстуры, используемые в сцене, в выходной каталог. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Имя | Описание |
| --- | --- |
| getFileFormat() | Получает формат файла, указанный в текущей опции Сохранить/Загрузить. |

 **Result:**



---


### getEncoding{#getEncoding}

| Имя | Описание |
| --- | --- |
| getEncoding() | Получает или задает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Имя | Описание |
| --- | --- |
| getFileSystem() | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Имя | Описание |
| --- | --- |
| setFileSystem(value) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Имя | Описание |
| --- | --- |
| getLookupPaths() | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |

 **Result:**



---


### getFileName{#getFileName}

| Имя | Описание |
| --- | --- |
| getFileName() | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Имя | Описание |
| --- | --- |
| setFileName(value) | Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ. |

 **Result:**



---



