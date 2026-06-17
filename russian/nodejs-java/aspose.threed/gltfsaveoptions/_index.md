---
title: "GltfSaveOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Параметры сохранения для формата glTF.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(contentType) | Конструктор GltfSaveOptions |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(format) | Конструктор GltfSaveOptions |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| forma | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Имя | Описание |
| --- | --- |
| getPrettyPrint() | Содержимое JSON файла GLTF отступается для удобства чтения человеком, значение по умолчанию — false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Имя | Описание |
| --- | --- |
| setPrettyPrint(value) | Содержимое JSON файла GLTF отступается для удобства чтения человеком, значение по умолчанию — false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Имя | Описание |
| --- | --- |
| getFallbackNormal() | Когда экспортер GLTF2 обнаружил недопустимую нормаль, будет использовано это значение вместо оригинального, чтобы обойти проверку. Значение по умолчанию — (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Имя | Описание |
| --- | --- |
| getEmbedAssets() | Встраивает все внешние ресурсы в виде base64 в один файл в режиме ASCII, значение по умолчанию — false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Имя | Описание |
| --- | --- |
| setEmbedAssets(value) | Встраивает все внешние ресурсы в виде base64 в один файл в режиме ASCII, значение по умолчанию — false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Имя | Описание |
| --- | --- |
| getImageFormat() | Стандартный glTF поддерживает только PNG/JPG в качестве формата текстур, эта опция определяет, как Aspose.3D будет конвертировать нестандартные изображения в поддерживаемый формат во время экспорта. Значение по умолчанию — GltfEmbeddedImageFormat.PNG. Значение свойства — целочисленная константа GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Имя | Описание |
| --- | --- |
| setImageFormat(value) | Стандартный glTF поддерживает только PNG/JPG в качестве формата текстур, эта опция определяет, как Aspose.3D будет конвертировать нестандартные изображения в поддерживаемый формат во время экспорта. Значение по умолчанию — GltfEmbeddedImageFormat.PNG. Значение свойства — целочисленная константа GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Имя | Описание |
| --- | --- |
| getMaterialConverter() | Пользовательский конвертер для преобразования материала геометрии в материал PBR. Если он не назначен, экспортёр glTF 2.0 автоматически преобразует стандартный материал в материал PBR. Значение по умолчанию — null. Это свойство используется при экспорте сцены в файл glTF 2.0. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Имя | Описание |
| --- | --- |
| setMaterialConverter(value) | Пользовательский конвертер для преобразования материала геометрии в материал PBR. Если он не назначен, экспортёр glTF 2.0 автоматически преобразует стандартный материал в материал PBR. Значение по умолчанию — null. Это свойство используется при экспорте сцены в файл glTF 2.0. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Имя | Описание |
| --- | --- |
| getUseCommonMaterials() | Сериализовать материалы с использованием расширений общих материалов KHR, значение по умолчанию — false. Установка этого параметра в false приведёт к тому, что Aspose.3D экспортирует набор вершинных/фрагментных шейдеров, если #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Имя | Описание |
| --- | --- |
| setUseCommonMaterials(value) | Сериализовать материалы с использованием расширений общих материалов KHR, значение по умолчанию — false. Установка этого параметра в false приведёт к тому, что Aspose.3D экспортирует набор вершинных/фрагментных шейдеров, если #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Имя | Описание |
| --- | --- |
| getExternalDracoEncoder() | Использовать внешний кодировщик Draco для ускорения скорости сжатия Draco. Aspose.3D создаст новый подпроцесс для кодирования сетки в формат Draco, используйте его на свой страх и риск. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Имя | Описание |
| --- | --- |
| setExternalDracoEncoder(value) | Использовать внешний кодировщик Draco для ускорения скорости сжатия Draco. Aspose.3D создаст новый подпроцесс для кодирования сетки в формат Draco, используйте его на свой страх и риск. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Имя | Описание |
| --- | --- |
| getFlipTexCoordV() | Отразить компонент координаты текстуры v(t), значение по умолчанию — true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Имя | Описание |
| --- | --- |
| setFlipTexCoordV(value) | Отразить компонент координаты текстуры v(t), значение по умолчанию — true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Имя | Описание |
| --- | --- |
| getBufferFile() | Имя внешнего буферного файла, используемого для хранения бинарных данных. Если этот файл не указан, Aspose.3D сгенерирует имя автоматически. Этот параметр игнорируется при экспорте glTF в бинарном режиме. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Имя | Описание |
| --- | --- |
| setBufferFile(value) | Имя внешнего буферного файла, используемого для хранения бинарных данных. Если этот файл не указан, Aspose.3D сгенерирует имя автоматически. Этот параметр игнорируется при экспорте glTF в бинарном режиме. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Имя | Описание |
| --- | --- |
| getSaveExtras() | Сохранять динамические свойства объектов сцены в поля 'extra' генерируемого файла glTF. Это полезно для предоставления данных, специфичных для приложения. Значение по умолчанию — false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Имя | Описание |
| --- | --- |
| setSaveExtras(value) | Сохранять динамические свойства объектов сцены в поля 'extra' генерируемого файла glTF. Это полезно для предоставления данных, специфичных для приложения. Значение по умолчанию — false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Имя | Описание |
| --- | --- |
| getApplyUnitScale() | Применить AssetInfo.UnitScaleFactor к сетке. Значение по умолчанию — false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Имя | Описание |
| --- | --- |
| setApplyUnitScale(value) | Применить AssetInfo.UnitScaleFactor к сетке. Значение по умолчанию — false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Имя | Описание |
| --- | --- |
| getDracoCompression() | Получает или задаёт, включено ли сжатие Draco |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Имя | Описание |
| --- | --- |
| setDracoCompression(value) | Получает или задаёт, включено ли сжатие Draco |

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



