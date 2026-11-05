---
title: "TextureData"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Bu sınıf, bir dokunun ham verilerini ve format tanımını içerir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | TextureData yapıcı |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| widt | Sayı | null |
| heigh | Sayı | null |
| strid | Sayı | null |
| bytesPerPixe | Sayı | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Yeni bir TextureData oluşturur ve piksel verilerini ayırır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| widt | Sayı | null |
| heigh | Sayı | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2() | TextureData yapıcı |

 **Result:**



---


### getData{#getData}

| Ad | Açıklama |
| --- | --- |
| getData() | Piksel verilerinin ham baytları |

 **Result:**



---


### getWidth{#getWidth}

| Ad | Açıklama |
| --- | --- |
| getWidth() | Yatay piksel sayısı |

 **Result:**



---


### getHeight{#getHeight}

| Ad | Açıklama |
| --- | --- |
| getHeight() | Dikey piksel sayısı |

 **Result:**



---


### getStride{#getStride}

| Ad | Açıklama |
| --- | --- |
| getStride() | Bir tarama satırının bayt sayısı. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Ad | Açıklama |
| --- | --- |
| getBytesPerPixel() | Bir pikselin bayt sayısı |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Ad | Açıklama |
| --- | --- |
| getPixelFormat() | Pikselin formatı Özelliğin değeri PixelFormat tam sayı sabitidir. |

 **Result:**



---


### fromFile{#fromFile}

| Ad | Açıklama |
| --- | --- |
| fromFile(fileName) | Bir dosyadan doku yükle |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| Ad | Açıklama |
| --- | --- |
| save(fileName) | Doku verilerini görüntü dosyasına kaydet |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Görüntünün kaydedileceği dosyanın adı. |

 **Result:**
TextureData


---


### save{#save}

| Ad | Açıklama |
| --- | --- |
| save(fileName, format) | Doku verilerini görüntü dosyasına kaydet |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Görüntünün kaydedileceği dosyanın adı. |
| format | String | Çıktı dosyasının görüntü formatı. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Ad | Açıklama |
| --- | --- |
| mapPixels(mapMode) | Tüm pikselleri okuma/yazma için eşle |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Ad | Açıklama |
| --- | --- |
| mapPixels(mapMode, format) | Verilen piksel formatında tüm pikselleri okuma/yazma için eşle |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Ad | Açıklama |
| --- | --- |
| mapPixels(rect, mapMode, format) | Verilen piksel formatında, rect tarafından adreslenen pikselleri okuma/yazma için eşle |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rect | Rect | Erişilecek piksel alanı |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Ad | Açıklama |
| --- | --- |
| transformPixelFormat(pixelFormat) | Pikselin düzenini yeni piksel formatına dönüştür. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



