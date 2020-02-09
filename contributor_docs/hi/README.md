नमस्कार! P5.js में योगदान देने में आपकी रुचि के लिए धन्यवाद! आप [यहाँ](https://p5js.org/community/#contribute) योगदान करने के कुछ अलग तरीकों से शुरुआत कर सकते हैं। इस फ़ोल्डर में p5.js. के डेवलपर्स के लिए विभिन्न दस्तावेज़ हैं।

# प्रोजेक्ट डायरेक्टरी स्ट्रक्चर

- `src/` में पुस्तकालय के लिए सभी स्रोत कोड शामिल हैं, जो अलग-अलग मॉड्यूल में शीर्ष रूप से व्यवस्थित है। यदि आप p5.js. बदल रहे हैं, तो आप इस पर काम करेंगे
- `lib/` में उपयोगकर्ताओं के लिए अपने स्केच और प्रोजेक्ट में लोड करने के लिए p5.js का अंतिम संस्करण है, जिसमें संपीड़ित और असम्बद्ध दोनों रूप शामिल हैं। यह स्रोत कोड मॉड्यूल [ग्रन्ट](https://gruntjs.com/) द्वारा एक फ़ाइल में संकलित किए जाने पर आउटपुट होता है।
- 'contributor_docs/' में विभिन्न मार्कडाउन दस्तावेज हैं, जो विशेष रूप से p5.js के डेवलपर्स के लिए उपयोगी होने की संभावना है, क्योंकि वे प्रथाओं और सिद्धांतों की व्याख्या करते हैं।
- `docs/` वास्तव में डॉक्स शामिल नहीं है! इसके बजाय, इसमें * [ऑनलाइन संदर्भ पुस्तिका](https://p5js.org/reference/) * का उपयोग करने वाला कोड शामिल है।
- `tests/` में यूनिट परीक्षण शामिल हैं जो सुनिश्चित करते हैं कि पुस्तकालय सही ढंग से कार्य कर रहे हैं क्योंकि परिवर्तन किए जाते हैं।
- `tasks/` में स्क्रिप्ट शामिल हैं जो पी 5 के नए संस्करणों के निर्माण, परिनियोजन और रिलीज़ से संबंधित स्वचालित कार्य करते हैं।
- `patches/` में समय-समय पर [गिट पैच](https://git-scm.com/docs/git-format-patch) शामिल हो सकते हैं, लेकिन लगभग सभी मामलों में आप इस निर्देशिका को पूरी तरह से अनदेखा कर सकते हैं।

# कैसे करें योगदान

ज्ञात बग और इच्छित नई सुविधाओं को [गिटहब मुद्दों](https://github.com/processing/p5.js/issues) का उपयोग करके ट्रैक किया जाता है। अंक [लेबल](./issue_labels.md) को श्रेणियों में मुद्दों को सुलझाने के लिए उपयोग किया जाता है, जैसे कि जो [शुरुआती के लिए उपयुक्त हैं](https://github.com/processing/p5.js/labels/level%3Abeginner) । यदि आप किसी मौजूदा मुद्दे पर काम करना शुरू करना चाहते हैं, तो इस मुद्दे पर टिप्पणी करें कि आप इस पर काम करने की योजना बना रहे हैं ताकि अन्य योगदानकर्ताओं को पता चल सके कि यह काम कर रहा है और मदद की पेशकश कर सकता है। एक बार जब आप इस मुद्दे पर अपना काम पूरा कर लेते हैं, तो p5.js मास्टर शाखा के खिलाफ [एक पुल निवेदन (PR)](./preparing_a_pull_request.md) जमा करें। पीआर के विवरण क्षेत्र में, "आप जो फिक्सिंग कर रहे हैं उस समस्या को टैग करते हुए" #XXXX "को हल करें।" यदि पीआर समस्या को संबोधित करता है, लेकिन इसे पूरी तरह से हल नहीं करता है (यानी आपके पीआर विलय के बाद समस्या खुली रहनी चाहिए), "पते #XXX" लिखें।

यदि आपको एक बग की खोज है या एक नई सुविधा के लिए एक विचार है जिसे आप जोड़ना चाहते हैं, तो एक समस्या सबमिट करके शुरू करें। कृपया बिना किसी समस्या के बस एक पुल अनुरोध प्रस्तुत करें जिसमें पहले कोई समस्या न हो, हम इसे स्वीकार नहीं कर पाएंगे। एक बार जब आप इस मुद्दे पर कुछ प्रतिक्रिया प्राप्त कर लेते हैं और इसे संबोधित करने के लिए आगे बढ़ते हैं, तो आप फ़िक्सेस या फ़ीचर को योगदान करने के लिए ऊपर की प्रक्रिया का पालन कर सकते हैं।

आप उन समस्याओं को ट्राइएज कर सकते हैं जिनमें बग रिपोर्ट को पुन: प्रस्तुत करना या महत्वपूर्ण जानकारी मांगना शामिल हो सकता है, जैसे कि संस्करण संख्या या प्रजनन निर्देश। यदि आप त्रिकोणीय मुद्दों को शुरू करना चाहते हैं, तो आरंभ करने का एक आसान तरीका है [CodeTriage पर p5.js की सदस्यता लें](https://www.codetriage.com/processing/p5.js)। [![ओपन सोर्स हेल्पर्स](https://www.codetriage.com/processing/p5.js/badges/users.svg)](https://www.codetriage.com/processing/p5.js)

हम सभी प्रकार के योगदानों को पहचानते हैं। यह परियोजना [सभी योगदानकर्ताओं](https://github.com/kentcdodds/all-contributors) विनिर्देशन का अनुसरण करती है। [निर्देश यहाँ](https://github.com/processing/p5.js/issues/2309) का अनुसरण करके अपने आप को [रीडमी](https://github.com/processing/p5.js/blob/master/README.md#contributors) में जोड़ें।

## ैकपेनीमेंट्स

कोड के अलावा, आपको निम्नलिखित में से कुछ संयोजन की आपूर्ति करने की आवश्यकता हो सकती है।

- कोड टिप्पणियों के रूप में [इनलाइन दस्तावेज़ीकरण](./inline_documentation.md), जो अन्य डेवलपर्स और उपयोगकर्ताओं को कोड समझाता है। इन टिप्पणियों में से कई को [JSDoc](https://jsdoc.app) सिंटैक्स के अनुरूप होना चाहिए और इसे p5.js वेबसाइट पर [ऑनलाइन संदर्भ पुस्तिका](https://p5js.org/reference/) के हिस्से के रूप में प्रकाशित किया जाएगा।
- [इकाई परीक्षण](./unit_testing.md), कोड के छोटे टुकड़े जो लाइब्रेरी से अलग हैं और उनके व्यवहार को सत्यापित करने के लिए उपयोग किए जाते हैं।

## उदाहरण

P5.js साइट में [एकीकृत उदाहरण](http://p5js.org/examples/) शामिल हैं। आप [और जोड़ सकते हैं](https://github.com/processing/p5.js-website/blob/master/contributor_docs/Adding_examples.md), और एक मुद्दा है जो कुछ [वांछित उदाहरणों](https://github.com/processing/p5.js/issues/1954) को सूचीबद्ध करता है।

## ईएस6

p5.js हाल ही में [ES6](https://en.wikipedia.org/wiki/ECMAScript#6th_Edition_-_ECMAScript_2015) पर चले गए हैं। यह देखने के लिए कि यह परिवर्तन आपके योगदान को कैसे प्रभावित कर सकता है, कृपया [ES6 गोद लेने](./es6-adoption.md) पर जाएँ।

## अन्य विचार

यदि आप अन्य तरीकों से योगदान करना चाहते हैं, जो यहां शामिल नहीं हैं, तो [hello@p5js.org](mailto:hello@p5js.org) पर लिखने के लिए स्वतंत्र महसूस करें और हमें बताएं कि आप क्या सोच रहे हैं! इस कोडबेस पर काम करने के अलावा, हम हमेशा प्रलेखन, ट्यूटोरियल, कार्यशालाओं, शैक्षिक सामग्री, ब्रांडिंग और डिजाइन जैसी चीजों का उपयोग कर सकते हैं। संपर्क में रहें और हम उन तरीकों के बारे में बात कर सकते हैं जिनमें आप भाग ले सकते हैं।

# गोचास

P5.js कोडबेस के साथ शामिल डेवलपर टूलिंग जानबूझकर कुछ चीजों के बारे में बहुत सख्त है। यह एक अच्छी बात है! यह सब कुछ सुसंगत बनाता है, और यह आपको अनुशासित होने के लिए प्रोत्साहित करेगा। इसका मतलब यह है कि आप अपनी परियोजना को खारिज करने के लिए केवल कुछ बदलने की कोशिश कर सकते हैं, लेकिन निराश न हों; यहां तक ​​कि अनुभवी p5.js डेवलपर्स को हर समय इस सामान द्वारा पकड़ा जाता है। आमतौर पर समस्या दो क्षेत्रों में से एक में होगी।

## कोड सिंटैक्स

p5.js को स्वच्छ और शैलीगत सुसंगत कोड सिंटैक्स की आवश्यकता होती है, जिसे वह [Prettier](https://prettier.io/) और [ESlint](https://eslint.org/) के साथ लागू करता है। आपके द्वारा किए जाने से पहले नियमों की जाँच की जाती है, लेकिन जैसे ही आप उन्हें लिखते हैं, त्रुटियों को उजागर करने के लिए आप अपने कोड संपादक के लिए [ESlint प्लगइन](https://eslint.org/docs/user-guide/integrations#editors) भी स्थापित कर सकते हैं। , जो शायद आपकी मदद करेंगे क्योंकि आप कोडिंग कर रहे हैं और आपको एक असफल Git प्रतिबद्ध की परेशानी से बचाता है। सामान्य तौर पर, हम लचीलेपन के पक्ष में गलती करते हैं, जब यह कोड शैली की बात आती है, ताकि भागीदारी और योगदान के लिए बाधाओं को कम किया जा सके।

त्रुटियों का पता लगाने के लिए, अपने टर्मिनल में निम्न कमांड चलाएँ (`$` प्रांप्ट टाइप न करें):

```
$ npm run lint
```

कुछ सिंटैक्स त्रुटियां स्वचालित रूप से ठीक की जा सकती हैं:

```
$ npm run lint:fix
```

स्थापित परियोजना शैली के साथ चिपके रहना आमतौर पर बेहतर होता है, लेकिन [कभी-कभी](https://github.com/processing/p5.js/search?utf8=%E2%9C%93&q=prettier-ignore&type=) एक वैकल्पिक वाक्यविन्यास का उपयोग कर सकते हैं। अपने कोड को समझना आसान बनाएं। इन मामलों के लिए, Prettier [एक एस्केप हैच प्रदान करता है](https://prettier.io/docs/en/ignore.html), `// prettier-ignore` टिप्पणी, जिसका उपयोग आप ग्रैनुलर अपवाद बनाने के लिए कर सकते हैं। यदि आप कर सकते हैं तो इसका उपयोग करने से बचने की कोशिश करें, क्योंकि लाइनिंग द्वारा लागू अधिकांश शैली वरीयताओं के लिए अच्छे कारण हैं।

यहाँ कोड शैली नियमों का एक त्वरित सारांश है। कृपया ध्यान दें कि यह सूची अधूरी हो सकती है, और [.prettierrc](https://github.com/processing/p5.js/blob/master/.prettierrc) और [.esintintrc](https://github.com/processing/p5.js/blob/master/.eslintrc) को संदर्भित करना सबसे अच्छा है। 
* ES6 कोड सिंटैक्स का उपयोग किया जाता है
* सिंगल कोट्स (डबल कोट्स के बजाय) का उपयोग करें
* इंडेंटेशन दो स्थानों के साथ किया जाता है
* कोड में परिभाषित सभी चर का उपयोग कम से कम एक बार किया जाना चाहिए, या पूरी तरह से हटा दिया जाना चाहिए
* X == सत्य या x == असत्य की तुलना न करें। इसके बजाय (x) या (x) का उपयोग करें। x == सच, निश्चित रूप से अगर (x) से अलग है! यदि भ्रम की संभावना है, तो ऑब्जेक्ट्स को शून्य, संख्याओं से 0 या स्ट्रिंग्स की तुलना करें।
* जब भी आप लिख रहे हैं, तो कार्य में अस्पष्टता या जटिलता होने पर अपना कोड कमेंट करें।
* देखें [मोज़िला JS प्रथाओं](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Coding_Style#JavaScript_practices) अधिक स्टाइलिंग टिप्स के लिए एक उपयोगी मार्गदर्शिका के रूप में।

## यूनिट टेस्ट

यूनिट परीक्षण कोड के छोटे टुकड़े होते हैं जो प्राथमिक तर्क के पूरक के रूप में बनाए जाते हैं और सत्यापन करते हैं। यदि आप p5.js के लिए एक प्रमुख नई सुविधा विकसित कर रहे हैं, तो आपको शायद परीक्षण शामिल करना चाहिए। पुल अनुरोध सबमिट न करें जिसमें परीक्षण पास नहीं होते हैं, क्योंकि इसका मतलब है कि कुछ टूट गया है।

इकाई परीक्षण चलाने के लिए, आपको पहले परियोजना की निर्भरताएँ स्थापित करनी होंगी।

```
$ npm ci
```

यह p5.js के लिए *सभी* निर्भरताएं स्थापित करेगा; संक्षेप में, यूनिट परीक्षण के लिए सबसे महत्वपूर्ण निर्भरताएं शामिल हैं:

- [मोचा](https://mochajs.org/), एक शक्तिशाली परीक्षण ढाँचा जो व्यक्तिगत परीक्षण फ़ाइलों को निष्पादित करता है जो p5.js के लिए विशिष्ट हैं
- [मोचा-क्रोम](https://github.com/shellscape/mocha-chrome), एक मोचा प्लगइन जो बिना सिर के गूगल क्रोम का उपयोग करके मोचा परीक्षण चलाता है

एक बार निर्भरताएं स्थापित हो जाने के बाद, यूनिट परीक्षणों को चलाने के लिए ग्रंट का उपयोग करें।

```
$ grunt
```

कभी-कभी कमांड लाइन पर के बजाय ब्राउज़र में परीक्षण चलाना उपयोगी होता है। ऐसा करने के लिए, पहले [कनेक्ट](https://github.com/gruntjs/grunt-contrib-connect) सर्वर शुरू करें:

```
$ npm run dev
```

सर्वर के चलने के साथ, आपको एक ब्राउज़र में `test/test.html` खोलने में सक्षम होना चाहिए।

इकाई परीक्षण के लिए एक पूर्ण मार्गदर्शिका p5.js प्रलेखन के दायरे से परे है, लेकिन संक्षिप्त संस्करण यह है कि `src/` निर्देशिका में निहित स्रोत कोड में लागू किए गए किसी भी बड़े बदलाव या नई सुविधाओं को भी `test/` फ़ाइलों के साथ होना चाहिए लाइब्रेरी के सभी भविष्य के संस्करणों में लगातार व्यवहार को सत्यापित करने के लिए मोचा द्वारा निष्पादित किया जा सकता है। इकाई परीक्षण लिखते समय, अपने दावे संदेशों को फिर से प्रकाशित करने के लिए एक गाइड के रूप में [Chai.js संदर्भ](http://www.chaijs.com/api/assert/) का उपयोग करें ताकि भविष्य में आपके परीक्षणों द्वारा पकड़ी गई कोई भी त्रुटि हो। लगातार और परिणामस्वरूप अन्य के लिए आसान है

# विकास की प्रक्रिया

1. स्थापित करें [node.js](http://nodejs.org/), जो स्वचालित रूप से [npm](https://www.npmjs.org) पैकेज मैनेजर भी स्थापित करता है।
2. [फोर्क](https://help.github.com/articles/fork-a-repo) [p5.js रिपॉजिटरी](https://github.com/processing/p5.js) अपने खुद के गिटहब खाते में।
3. [क्लोन](https://help.github.com/articles/cloning-a-repository/) आपके स्थानीय कंप्यूटर पर गिटहब से रिपॉजिटरी का नया फोर्क।

   ```
   $ git clone https://github.com/YOUR_USERNAME/p5.js.git
   ```

4. प्रोजेक्ट फ़ोल्डर में नेविगेट करें और npm के साथ अपनी सभी आवश्यक निर्भरताएं स्थापित करें।

   ```
   $ cd p5.js
   $ npm ci
   ```

5. [ग्रंट](https://gruntjs.com/) अब स्थापित किया जाना चाहिए, और आप इसका उपयोग स्रोत कोड से लाइब्रेरी बनाने के लिए कर सकते हैं।

   ```
   $ npm run grunt
   ```

यदि आप लाइब्रेरी में लगातार फाइलों को बदल रहे हैं, तो आप अपने लिए लाइब्रेरी को स्वचालित रूप से पुनर्निर्माण करने के लिए `npm run dev` को चलाना चाहते हैं, जब भी इसका कोई भी सोर्स आपके बिना पहली बार मैन्युअल रूप से टाइप किए बिना बदल जाता है।

6. स्थानीय रूप से कोडबेस और [कमिट](https://help.github.com/articles/github-glossary/#commit) में कुछ बदलाव करें।

   ```
   $ git add -u
   $ git commit -m "YOUR COMMIT MESSAGE"
   ```

7. रन `npm run grunt` फिर से सुनिश्चित करें कि कोई सिंटैक्स त्रुटियां, परीक्षण विफलताओं, या अन्य समस्याएं नहीं हैं।

8. [पुश](https://help.github.com/articles/github-glossary/#push) गिटहब पर आपके फोर्क में आपके नए परिवर्तन।

   ```
   $ git push
   ```

9. एक बार सब कुछ तैयार हो जाने के बाद, अपने परिवर्तनों को एक [पुल अनुरोध](https://help.github.com/articles/creating-a-pull-request) के रूप में सबमिट करें।

यह प्रक्रिया [कोडिंग ट्रेन द्वारा एक वीडियो में](https://youtu.be/Rr3vLyP1Ods) भी शामिल है। :train::rainbow:

# बिल्डिंग डॉक्यूमेंटेशन

P5.js में इनलाइन टिप्पणियां सार्वजनिक-सामना [संदर्भ मैनुअल](https://p5js.org/reference/) में बनाई गई हैं। आप इसे स्थानीय रूप से भी देख सकते हैं:

```
$ npm run docs:dev
```

# रिपोजिटरी

ओवररचिंग p5.js प्रोजेक्ट में इसके अलावा अन्य रिपॉजिटरी शामिल हैं।

- [p5.js](https://github.com/processing/p5.js): इस रिपॉजिटरी में p5.js लाइब्रेरी का सोर्स कोड है। इस स्रोत कोड में शामिल [JSDoc](http://usejsdoc.org/) टिप्पणियों से [उपयोगकर्ता-सामना करने वाला p5.js संदर्भ मैनुअल](https://p5js.org/reference/) भी उत्पन्न होता है। इसका रखरखाव [लॉरेन मैकार्थी](https://github.com/lmccart) द्वारा किया जाता है।
- [वेबसाइट](https://github.com/processing/p5.js-website) इस रिपॉजिटरी में [p5.js वेबसाइट](http://p5js.org), के अपवाद के साथ अधिकांश कोड हैं। संदर्भ मैनुअल। इसका रखरखाव [लॉरेन मैकार्थी](https://github.com/lmccart) द्वारा किया जाता है।
- [ध्वनि](https://github.com/processing/p5.js-sound) इस रिपॉजिटरी में p5.sound.js लाइब्रेरी है। इसका रखरखाव [जेसन सिगल](https://github.com/therewasaguy) करता है।
- [वेब एडिटर](https://github.com/processing/p5.js-web-editor): इस रिपॉजिटरी में [p5.js वेब एडिटर] के लिए सोर्स कोड शामिल है(https://editor.p5js.org )। इसका रखरखाव [कैसी तारकजियान](https://github.com/catarak) द्वारा किया जाता है। ध्यान दें कि पुराना [p5.js संपादक](https://github.com/processing/p5.js-editor) अब पदावनत हो गया है।

# विविध

- (लुकिंग इनसाइड p5.js](http://www.luisapereira.net/teaching/looking-inside-p5/) p5.js डेवलपमेंट वर्कफ़्लो में इस्तेमाल होने वाले टूल्स और फाइल्स का वीडियो टूर है।
- p5.js [डॉकर छवि](https://github.com/toolness/p5.js-docker) [डॉकर](https://www.docker.com/) में आरोहित किया जा सकता है और इसका उपयोग p5 विकसित करने के लिए किया जाता है [नोड](https://nodejs.org/) जैसी आवश्यकताओं की मैन्युअल स्थापना की आवश्यकता के बिना .js या अन्यथा डॉकर की स्थापना से अलग किसी भी तरह से मेजबान ऑपरेटिंग सिस्टम को प्रभावित करना।
- p5.js लाइब्रेरी के लिए निर्माण प्रक्रिया एक [json डेटा फ़ाइल](https://p5js.org/reference/data.json) उत्पन्न करती है, जिसमें p5.js की सार्वजनिक API होती है और इसका उपयोग स्वचालित टूलिंग में किया जा सकता है, जैसे एक संपादक में स्वतः पूर्ण p5.js विधियों के रूप में। यह फ़ाइल p5.js वेबसाइट पर होस्ट की गई है, लेकिन यह रिपॉजिटरी के हिस्से के रूप में शामिल नहीं है।