---
title: "TextureData"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

هذه الفئة تحتوي على البيانات الخام وتعريف التنسيق لقوام.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | منشئ TextureData |

 **Parameters:**

| الاسم | النوع | الوصف |
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

| الاسم | الوصف |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | ينشئ كائنًا جديدًا من TextureData ويخصص بيانات البكسل. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| widt | Number | null |
| heigh | Number | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2() | منشئ TextureData |

 **Result:**



---


### getData{#getData}

| الاسم | الوصف |
| --- | --- |
| getData() | البتات الخام لبيانات البكسل |

 **Result:**



---


### getWidth{#getWidth}

| الاسم | الوصف |
| --- | --- |
| getWidth() | عدد البكسلات الأفقية |

 **Result:**



---


### getHeight{#getHeight}

| الاسم | الوصف |
| --- | --- |
| getHeight() | عدد البكسلات العمودية |

 **Result:**



---


### getStride{#getStride}

| الاسم | الوصف |
| --- | --- |
| getStride() | عدد البايتات في سطر المسح. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| الاسم | الوصف |
| --- | --- |
| getBytesPerPixel() | عدد البايتات في البكسل |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| الاسم | الوصف |
| --- | --- |
| getPixelFormat() | تنسيق البكسل. قيمة الخاصية هي ثابت عدد صحيح من نوع PixelFormat. |

 **Result:**



---


### fromFile{#fromFile}

| الاسم | الوصف |
| --- | --- |
| fromFile(fileName) | تحميل نسيج من ملف |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| الاسم | الوصف |
| --- | --- |
| save(fileName) | احفظ بيانات القوام في ملف صورة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف حيث سيتم حفظ الصورة. |

 **Result:**
TextureData


---


### save{#save}

| الاسم | الوصف |
| --- | --- |
| save(fileName, format) | احفظ بيانات القوام في ملف صورة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف حيث سيتم حفظ الصورة. |
| format | String | تنسيق الصورة للملف الناتج. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| الاسم | الوصف |
| --- | --- |
| mapPixels(mapMode) | تعيين جميع البكسلات للقراءة/الكتابة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| الاسم | الوصف |
| --- | --- |
| mapPixels(mapMode, format) | تعيين جميع البكسلات للقراءة/الكتابة بالتنسيق البكسلي المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| الاسم | الوصف |
| --- | --- |
| mapPixels(rect, mapMode, format) | تعيين البكسلات المحددة بواسطة المستطيل للقراءة/الكتابة بالتنسيق البكسلي المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rect | Rect | منطقة البكسلات التي سيتم الوصول إليها |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| الاسم | الوصف |
| --- | --- |
| transformPixelFormat(pixelFormat) | تحويل تخطيط البكسل إلى تنسيق بكسلي جديد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



