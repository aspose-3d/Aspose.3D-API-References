---
title: "Metered"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/metered/
---
## Metered class

मीटर की कुंजी सेट करने के लिए विधियाँ प्रदान करता है।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor() | इस क्लास का एक नया इंस्टेंस आरंभ करता है। |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| नाम | विवरण |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | मीटरड सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटरड लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफलता रहती है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट किया जाएगा; ऐसी स्थिति से बचने के लिए आपको नियमित रूप से लाइसेंस स्थिति जांचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| publicKey | स्ट्रिंग | सार्वजनिक कुंजी |
| privateKey | स्ट्रिंग | निजी कुंजी |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| नाम | विवरण |
| --- | --- |
| getConsumptionQuantity() | उपभोग फ़ाइल आकार प्राप्त करता है |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| नाम | विवरण |
| --- | --- |
| getConsumptionCredit() | उपभोग क्रेडिट प्राप्त करता है |

 **Result:**
BigDecimal


---



