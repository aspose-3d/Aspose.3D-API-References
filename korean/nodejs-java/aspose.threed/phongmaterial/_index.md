---
title: "PhongMaterial"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/phongmaterial/
---
## PhongMaterial class

blinn-phong 셰이딩 모델용 Material.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | PhongMaterial 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(name) | PhongMaterial 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### getSpecularColor{#getSpecularColor}

| 이름 | 설명 |
| --- | --- |
| getSpecularColor() | 반사광 색상을 가져오거나 설정합니다. |

 **Result:**



---


### setSpecularColor{#setSpecularColor}

| 이름 | 설명 |
| --- | --- |
| setSpecularColor(value) | 반사광 색상을 가져오거나 설정합니다. |

 **Result:**



---


### getSpecularFactor{#getSpecularFactor}

| 이름 | 설명 |
| --- | --- |
| getSpecularFactor() | 반사광 계수를 가져오거나 설정합니다. 반사광 공식: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### setSpecularFactor{#setSpecularFactor}

| 이름 | 설명 |
| --- | --- |
| setSpecularFactor(value) | 반사광 계수를 가져오거나 설정합니다. 반사광 공식: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### getShininess{#getShininess}

| 이름 | 설명 |
| --- | --- |
| getShininess() | 광택도를 가져오거나 설정합니다. 이는 반사광 하이라이트의 크기를 제어합니다. 반사광 공식: SpecularColor SpecularFactor (N dot H) ^ Shininess 광택도. |

 **Result:**



---


### setShininess{#setShininess}

| 이름 | 설명 |
| --- | --- |
| setShininess(value) | 광택도를 가져오거나 설정합니다. 이는 반사광 하이라이트의 크기를 제어합니다. 반사광 공식: SpecularColor SpecularFactor (N dot H) ^ Shininess 광택도. |

 **Result:**



---


### getReflectionColor{#getReflectionColor}

| 이름 | 설명 |
| --- | --- |
| getReflectionColor() | 반사 색상을 가져오거나 설정합니다. 반사. |

 **Result:**



---


### setReflectionColor{#setReflectionColor}

| 이름 | 설명 |
| --- | --- |
| setReflectionColor(value) | 반사 색상을 가져오거나 설정합니다. 반사. |

 **Result:**



---


### getReflectionFactor{#getReflectionFactor}

| 이름 | 설명 |
| --- | --- |
| getReflectionFactor() | 반사 색상의 감쇠를 가져오거나 설정합니다. 반사 계수. |

 **Result:**



---


### setReflectionFactor{#setReflectionFactor}

| 이름 | 설명 |
| --- | --- |
| setReflectionFactor(value) | 반사 색상의 감쇠를 가져오거나 설정합니다. 반사 계수. |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| 이름 | 설명 |
| --- | --- |
| getEmissiveColor() | 방출 색상을 가져오거나 설정합니다. |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 이름 | 설명 |
| --- | --- |
| setEmissiveColor(value) | 방출 색상을 가져오거나 설정합니다. |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| 이름 | 설명 |
| --- | --- |
| getAmbientColor() | 주변 색상을 가져오거나 설정합니다. 예시: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| 이름 | 설명 |
| --- | --- |
| setAmbientColor(value) | 주변 색상을 가져오거나 설정합니다. 예시: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| 이름 | 설명 |
| --- | --- |
| getDiffuseColor() | 확산 색상을 가져오거나 설정합니다. 예시: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); 확산. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| 이름 | 설명 |
| --- | --- |
| setDiffuseColor(value) | 확산 색상을 가져오거나 설정합니다. 예시: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); 확산. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| 이름 | 설명 |
| --- | --- |
| getTransparentColor() | 투명 색상을 가져오거나 설정합니다. 예시: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); 투명 색상. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| 이름 | 설명 |
| --- | --- |
| setTransparentColor(value) | 투명 색상을 가져오거나 설정합니다. 예시: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); 투명 색상. |

 **Result:**



---


### getTransparency{#getTransparency}

| 이름 | 설명 |
| --- | --- |
| getTransparency() | 투명도 계수를 가져오거나 설정합니다. 이 계수는 0(0%, 완전 불투명)과 1(100%, 완전 투명) 사이여야 합니다. 잘못된 계수 값은 클램프됩니다. 예시: var mat = new LambertMaterial(); mat.Transparency = 0.3; 투명도 계수. |

 **Result:**



---


### setTransparency{#setTransparency}

| 이름 | 설명 |
| --- | --- |
| setTransparency(value) | 투명도 계수를 가져오거나 설정합니다. 이 계수는 0(0%, 완전 불투명)과 1(100%, 완전 투명) 사이여야 합니다. 잘못된 계수 값은 클램프됩니다. 예시: var mat = new LambertMaterial(); mat.Transparency = 0.3; 투명도 계수. |

 **Result:**



---


### getName{#getName}

| 이름 | 설명 |
| --- | --- |
| getName() | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### setName{#setName}

| 이름 | 설명 |
| --- | --- |
| setName(value) | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### getProperties{#getProperties}

| 이름 | 설명 |
| --- | --- |
| getProperties() | 모든 속성의 컬렉션을 가져옵니다. |

 **Result:**



---


### getTexture{#getTexture}

| 이름 | 설명 |
| --- | --- |
| getTexture(slotName) | 지정된 슬롯에서 텍스처를 가져옵니다. 이는 재질의 속성 이름이거나 셰이더의 매개변수 이름일 수 있습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| slotName | String | 슬롯 이름. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| 이름 | 설명 |
| --- | --- |
| setTexture(slotName, texture) | 지정된 슬롯에 텍스처를 설정합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| slotName | String | 슬롯 이름. |
| texture | TextureBase | 텍스처. |

 **Result:**
TextureBase


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 객체를 문자열로 포맷합니다. |

 **Result:**
String


---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 동적 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | 속성 | 제거할 속성은 무엇입니까 |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 이름으로 식별된 지정된 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 이름 | 설명 |
| --- | --- |
| getProperty(property) | 지정된 속성의 값을 가져옵니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |

 **Result:**
Object


---


### setProperty{#setProperty}

| 이름 | 설명 |
| --- | --- |
| setProperty(property, value) | 지정된 속성의 값을 설정합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |
| value | Object | 속성의 값 |

 **Result:**
Object


---


### findProperty{#findProperty}

| 이름 | 설명 |
| --- | --- |
| findProperty(propertyName) | 속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성(Identified by its name) 일 수 있습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propertyName | String | 속성 이름. |

 **Result:**
속성


---


### iterator{#iterator}

| 이름 | 설명 |
| --- | --- |
| iterator() | 내부 사용을 위해 예약되었습니다. |

 **Result:**
속성


---



