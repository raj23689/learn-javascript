---
chapter: अध्याय ६
pageNumber: ४०
titleIndex: ६.१
---
# अनशिफ्ट

`अनशिफ्ट` विधिले एरेको सुरुमा, वा अगाडि क्रमिक रूपमा नयाँ तत्वहरू थप्दछ। यसले मूल सरणीलाई परिमार्जन गर्दछ र सरणीको नयाँ लम्बाइ फर्काउँछ। उदाहरणका लागि.

```javascript
let array = [0, 5, 10];
array.unshift(-5);  // 4

// RESULT: array = [-5 , 0, 5, 10];
```

{% hint style="warning" %}

`unshift()` विधिले मूल सरणीलाई अधिलेखन गर्दछ।

{% endhint %}

`अनशिफ्ट` विधिले एक वा बढी तर्कहरू लिन्छ, जसले सरणीको सुरुमा थपिने तत्वहरूको प्रतिनिधित्व गर्दछ। यसले तत्वहरू प्रदान गरिएको क्रममा थप्दछ, त्यसैले पहिलो तत्व सरणीको पहिलो तत्व हुनेछ।

एरेमा बहुविध तत्वहरू थप्न `अनशिफ्ट` प्रयोग गर्ने उदाहरण यहाँ छ:

```javascript
const numbers = [1, 2, 3];
const newLength = numbers.unshift(-1, 0);
console.log(numbers); // [-1, 0, 1, 2, 3]
console.log(newLength); // 5
```
