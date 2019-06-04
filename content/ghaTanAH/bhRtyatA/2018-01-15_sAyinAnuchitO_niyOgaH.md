---
date_end: '2018-01-15'
cast:
- सायिः
- विश्वासः
date: '2018-01-15'
rasyataa: 4
title: सायिनानुचितो नियोगः
topics:
- कुनियोगः
- नयन्तृ-भृत्य-विवादः

---

## विवरणम्
प्रभावराहित्येन गात्रेण च कुत्सिते कार्ये नियुक्तो विश्वासः तदनौचित्यम् अकथयत्। लघुवादे ऽपि जाते न निष्कर्षं तत्पक्षतो ऽलभत।

## तत्र संवादः

Subject: Python Script to invoke samsadhani api  
From: Sai Susarla <sai.susarla@gmail.com>  
Date: 2018-01-17 20:00 GMT-08:00  
To: vishvAs vAsuki <vishvas.vasuki@gmail.com>  


Etat siddham asti kim?   
Kutra drashtum shakyate?   

----------
From: विश्वासो वासुकिजः (Vishvas Vasuki) <vishvas.vasuki@gmail.com>  
Date: 2018-01-17 20:33 GMT-08:00  
To: Sai Susarla <sai.susarla@gmail.com>  

​  
पुरा चर्चितम् स्मारयामि, यस्मिन् भवदभीप्सितं सिद्धं स्यात् -  

> 11/21/2017  
> सायिः: Bhoh, do you have the python script for invoking our grammar apis ready?  
> सायिः: I need it urgently for sentence generation work this weekend.  
> सायिः: Thank you.  

```
…  
विश्वासः: curl -X GET "https://api.vedavaapi.org/scala/grammar/v1/generators/alternateFormsWx/yAwi/karwari/lot/pra/1/parasmEpaxI" -H "accept: application/json" iti tu siddham - python wrapper rachanIyam.  
…  
विश्वासः: 
import requests  
url = "https://api.vedavaapi.org/scala/grammar/v1/generators/alternateFormsWx/yAwi/karwari/lot/pra/1/parasmEpaxI"  
response = requests.get(url)  
response.json()  


asya phalam:  
[u'yAwAw', u'yAwu']  

itopi kimapi wrapping nAvashyakam iti manye.  
```

ततः परम् दूरवाणी सम्भाषणेषु भवतेत्थं प्रार्थितम्  - "एकस्यैव धातोर् अनेकानि रूपाणी शीघ्रम् आवश्यकं स्यात् - पौनःपुन्येन REST API आह्वानम् अनुचितम्, अतः कस्मिंश्चिल् लकारे सर्वाणि रूपाणि युगपल् लब्धुं किमपि रचनीयम्"​। पश्चाच्च प्राक्तन-दूरवाणी-सम्भाषणात् परम् कदाचिद् एवं सम्भाषितम् -  

> विश्वासः: आर्य, वाक्यरचनायन्त्रं कीदृशं वाक्यं रचयेद् इति स्पष्टीकरोतु।  
> 
> grammar कोशे क्व च वाक्यरचनादेशास् सन्ति? न दृश्यन्ते। यदि सन्ति, तद् भागम् उद्धृत्य रचयामि यन्त्रं तद् अन्यत्र।  
> सायिः: Avashyam preshayishyaami​  

ततो न किमपि लब्धम्। किञ्च "एकस्यैव धातोर् अनेकानि रूपाणी शीघ्रम् आवश्यकं स्यात् - पौनःपुन्येन REST API आह्वानम् अनुचितम्, अतः कस्मिंश्चिल् लकारे सर्वाणि रूपाणि युगपल् लब्धुं किमपि रचनीयम्"​ इति यदिष्टं तस्य पूर्तिः धवलाविनाशाभ्यां रच्यमानेन तन्त्रांशेनाचिराद् भविष्यतीति न तत्र श्रमो नाशितः। तावत् "11/21/2017" इत्यस्मिन् दिन उक्तं तन्त्रं प्रयुनक्तु भवान्।  



Vishvas /विश्वासः  


----------
From: Sai Susarla <sai.susarla@gmail.com>  
Date: 2018-01-17 20:42 GMT-08:00  
To: vishvAs vAsuki <vishvas.vasuki@gmail.com>  


I need a wrapper around it that lets me specify the parameters in json which it internally converts to whatever url.   

----------
From: विश्वासो वासुकिजः (Vishvas Vasuki) <vishvas.vasuki@gmail.com>  
Date: 2018-01-17 20:54 GMT-08:00  
To: Sai Susarla <sai.susarla@gmail.com>  


 श्रीमन्, सादरम् ममाभिप्रायं कार्यसिसाधयिषया वच्मि, सक्षमः प्रतिगृह्णातु। you already know how to construct a URL like the below from the arguments yAwi, karwari, lot, pra, 1, parasmEpaxI:  
https://api.vedavaapi.org/scala/grammar/v1/generators/alternateFormsWx/yAwi/karwari/lot/pra/1/parasmEpaxI  

Micro-delegation is not a wise use of either of our time. If you don't have the time to write such a function, it means that you should not be writing that code at all. Delegation should be at a higher level. Please consider using this test - If it takes as much time to accurately specify what you want (preferably in writing) as it does to just do the task yourself - you should do it yourself. पुनरत्र परस्परतृप्तीच्छाम् अन्तरा न कश्चन दर्पादिकं मयि ग्राह्यम् आर्येण   

----------
From: Sai Susarla <sai.susarla@gmail.com>  
Date: 2018-01-18 1:09 GMT-08:00  
To: "विश्वासो वासुकिजः (Vishvas Vasuki)" <vishvas.vasuki@gmail.com>  


Priya vishvas,  
The purpose of my asking you to do this is not micro-delegation. There was a general message about how to make life easier for your customer by being sensitive about the broader intent and not just micro-respond to what they ask.  

When an API is published, to make it easier for people to use that API, one needs to provide a sample script that uses the API. The script should be more than a simple wrapper. It should blend seamlessly into the natural abstractions of the script's language. That script is going to be used as a template by a lot of people who are going to use your API. So it is very important provide a script that incorporates best practices.  

When I asked for a python script, I did not ask merely for a specific personal use - otherwise I would have written it myself. I am trying to play the role of a customer of your API. And as they say, the customer is always right. That's the golden rule for success. The key is to understand the customer's pain point.  

The time I am investing right now in micro-delegation is with the hope that I don't have to do that in the future.   
Whatever we put in the public domain as Vedavaapi API should be in a shape where people will find it easy to use and hence adopt widely. Attention to detail now helps reap rewards later.  

Please let me know if we need to discuss it further.  
- Sai.  



----------
From: विश्वासो वासुकिजः (Vishvas Vasuki) <vishvas.vasuki@gmail.com>  
Date: 2018-01-18 7:42 GMT-08:00  
To: Sai Susarla <sai.susarla@gmail.com>  


आदरपात्र सायिमहोदय,  

भवता व्यक्तिगतप्रयोगायैव वाक्यनिर्माणयन्त्रायैतद् अभीप्सितम् इति मया चिन्तितम्। एवं नेत्यधुना भवद्वचनात् परं ज्ञायते। तत्राऽपि वर्तते सन्देहः।  

* के नाम ते ग्राहका येभ्य एतादृशं‌ प्रोत्साहनम् अपेक्षितम्? कथं जानीयाम यत् ते भवतः‌ कल्पनायाम् एव न सन्तीति? तादृशाः सन्ति चेद् अपि तादृशानाम् अकुशलानां प्रोत्साहनेन किं महत् साध्येत? (ग्राहकैस् सह सम्पर्के, तदिष्टज्ञाने च ममास्ति दीर्घो ऽनुभवः। सन्ति नैके प्रयोक्तारोऽस्मत्प्रकाशितकोशानाम्, मद्रचित-आण्ड्रोय्ड्कोशस्थापकस्य। तेषु बहवो दोषान् सूचयन्तो विस्तारमिच्छन्तश्च कुर्वन्ति काले काले मत्सम्पर्कम्। एवञ्च साङ्गणकेष्वपि धवलाविनाश-मडत्तिलकार्त्तिक-रामसूनुकार्त्तिक-निभाः साङ्गणकग्राहकाः। एतेऽपि सूचना अददन् बहुदा। अहञ्चाप्यस्म्य् अन्येषां साङ्गणकानां‌ कृतीनाम् ग्राहकः। ते किं‌ कथं कुर्वन्तीत्यपि बहु दृष्टचरम्। )

​*‌ ​"The script should be more than a simple wrapper. It should blend seamlessly into the natural abstractions of the script's language." - अत्र wrapperतः‌ किमिष्यत इति नैव स्पष्टम्। उदाहरणेन दर्शयतु।  

* वास्तविकं वक्तव्यञ्चेत् धवलाविनाशाभ्यां (क्वचिन् मत्सूचनाभिः प्रेरिताभ्यां) प्रकाशयिष्यमानेन पैतान्-तन्त्रांशेन पैतान्-लेखकेष्व् अस्मत्तिङन्तजनकस्य प्रयोजनमेव न भविष्यतीत्यप्य् अवधेयम्। एवं शीघ्रं‌ जरति कर्मणि श्रमो न हि स्यात्।  

​* "Attention to detail now helps reap rewards later."​ - इत्यङ्गीकरोमि। कीदृशविवरणानीत्यत्र द्रष्टव्यम्। प्रभावशालीनि कर्माणि यतनीयानि, न क्षुद्राणि।  

अत्र​ नास्ति मम ​काचिदहङ्कृतिः। ​ "सम्मानाद्ब्राह्मणो नित्यं उद्विजेत विषादिव । अमृतस्येव चाकाङ्क्षेदवमानस्य सर्वदा"​ इति मनुवचनमेव मम प्रेरणं सर्वदा। एवं हि मच्चिन्तनादेः प्रामाणिके परिष्कारे मा भूत् सङ्कोचः।  


----------
From: विश्वासो वासुकिजः (Vishvas Vasuki) <vishvas.vasuki@gmail.com>  
Date: 2018-01-19 7:18 GMT-08:00  
To: Sai Susarla <sai.susarla@gmail.com>  


आर्यमिश्र, शुभवार्ता। पूर्वक्तधवलतन्त्रांशः सिद्धः।  

तत्प्रयोग एवम् - http://prakriya.readthedocs.io/en/latest/usage.html#generate-verb-forms  



Vishvas /विश्वासः  
