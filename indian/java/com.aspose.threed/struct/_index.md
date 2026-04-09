---
title: Struct
second_title: Aspose.3D for Java API Reference
description: lexchou द्वारा 13/11/2017 को बनाया गया।
type: docs
weight: 262
url: /hi/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

lexchou द्वारा 13/11/2017 को बनाया गया।
## Methods

| Method | विवरण |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | यदि यह Struct है तो इनपुट वैल्यू को कॉपी करने का प्रयास करें |
| [clone()](#clone--) | वर्तमान उदाहरण को क्लोन करें |
| [copyFrom(T t)](#copyFrom-T-) | आर्ग्यूमेंट t से आंतरिक स्थिति कॉपी करें |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


यदि यह Struct है तो इनपुट वैल्यू को कॉपी करने का प्रयास करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | T | क्लोन करने के लिए इनपुट वैल्यू |

**Returns:**
T - यदि इनपुट null है या क्लोन किया गया इंस्टेंस तो null
### clone() {#clone--}
```
public abstract T clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
T - क्लोन किया गया इंस्टेंस
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


आर्ग्यूमेंट t से आंतरिक स्थिति कॉपी करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| t | T | कॉपी करने के लिए स्रोत इंस्टेंस |

