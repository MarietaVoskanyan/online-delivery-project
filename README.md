# online delivery project
# Նկարագրություն
Այս աշխատանքում կիրառվել են մեքենայական ուսուցման մեթոդներ ուտելիքի օնլայն առաքման տվյալների վրա, կանխատեսելու համար` արդյոք հաճախորդը գոհ կլինի, թե դժգոհ: Նպատակն է պարզել թե ինչ գործոններ կարող են ազդել հաճախորդի կարծիքի վրա:
# Նպատակ
Կանխատեսել Output բինար փոփոխականը (1`գոհ, 0` դժգոհ)` օգտագործելով առաքման վերաբերյալ տարբեր հատկանիշներ:
#Հատկանիշների նկարագրություն

- Age: Օգտագործողի տարիքը
- Gender: Սեռը (0 ՝ կին, 1 ՝ տղամարդ)
- Marital Status: Ամուսնական կարգավիճակ
- Occupation: Զբաղվածություն (Student, Employee, Self Employeed, House wife)
- Monthly Income: Ամսական եկամուտ
- Educational Qualifications: Կրթական որակավորումներ
- Family size: Ընտանիքի անդամների քանակը
- latitude: Լայնություն (տեղակայում)
- longitude: Երկայնություն (տեղակայում)
- Pin code: Փոստային ինդեքս (ZIP)
- Medium (P1): Առաքման հարթակ (նախապատվություն 1)
- Medium (P2): Առաքման հարթակ (նախապատվություն 2)
- Meal(P1): Սննդի տեսակ (նախապատվություն 1)
- Meal(P2): Սննդի տեսակ (նախապատվություն 2)
- Perference(P1): Սննդի նախընտրություն (1-ին)
- Perference(P2): Սննդի նախընտրություն (2-րդ)
- Ease and convenient: Հարմարավետություն և դյուրինություն (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Time saving: Ժամանակի խնայողություն (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- More restaurant choices: Ավելի շատ ռեստորանների ընտրություն (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Easy Payment option: Հեշտ վճարման մեթոդ (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- More Offers and Discount: Ակցիաներ և զեղչեր (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Good Food quality: Բարձր սննդի որակ (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Good Tracking system: Լավ հետևման համակարգ (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Self Cooking: Ինքնուրույն պատրաստում (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Health Concern: Առողջության հետ կապված մտահոգություններ (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Late Delivery: Ոչ ժամանակին առաքում (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Poor Hygiene: Վատ հիգիենա (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Bad past experience: Վատ փորձ նախկինում (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Unavailability: Անհասանելիություն (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Unaffordable: Բարձր գին / անհասանելի գներով (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Long delivery time: Երկար առաքման ժամանակ (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Delay of delivery person getting assigned: Ուշացում առաքիչի նշանակման մեջ (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Delay of delivery person picking up food: Ուշացում սնունդը վերցնելու փուլում (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Wrong order delivered: Սխալ պատվերի առաքում (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Missing item: Պակաս ապրանք (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Order placed by mistake: Պատվերը սխալմամբ է գրանցվել (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Influence of time: Ժամանակի ազդեցությունը (Yes, No, Maybe)
- Order Time: Պատվերի գրանցման օրը (Weekend (Sat & Sun), Anytime (Mon-Sun), Weekdays (Mon-Fri))
- Maximum wait time: Սպասման առավելագույն ժամանակը
- Residence in busy location: Բնակության վայրը՝ մարդաշատ տարածքում (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Google Maps Accuracy: Google Քարտեզների ճշգրտություն (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Good Road Condition: Լավ ճանապարհային պայմաններ (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Low quantity low time: Քիչ քանակ՝ արագ առաքում (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Delivery person ability: Առաքիչի հմտությունները (Neutral, Strongly agree, Agree, Strongly disagree, Disagree)
- Influence of rating: Գնահատականի ազդեցությունը (Yes, No, Maybe)
- Less Delivery time: Ավելի կարճ առաքման ժամանակ (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- High Quality of package: Բարձր փաթեթավորման որակ (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- Number of calls: Զանգերի քանակ առաքման ընթացքում (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- Politeness: Քաղաքավարություն (առաքիչի) (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- Freshness: Թարմություն (ուտելիքի) (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- Temperature: Ջերմաստիճան (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- Good Taste: Համեղություն (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- Good Quantity: Բավարար քանակություն (Moderately Important, Very Important, Important, Slightly Important, Unimportant)
- Output: Թիրախային փոփոխական՝ գոհունակություն (Yes, No)
- Reviews: Օգտատերերի կարծիքներ

# Exploratory Data Analysis (EDA)
- Տվյալների ուսումնասիրություն և նախապատրաստում
- Թվային փոփոխականների բաշխումների վիզուալիզացիա
- Կոռելացիոն մատրիցի պատկերում
- համեմատական boxplot-եր ըստ 'Output'-ի

# Մոդելում օգտագործված հատկանիշները

Age, Gender, Marital Status, Occupation, Monthly Income, Educational Qualifications, Ease and convenient, Time saving, More restaurant choices, Easy Payment option, More Offers and Discount, Good Food quality, Good Tracking system, Residence in busy location, Google Maps Accuracy, Good Road Condition, Low quantity low time, Delivery person ability, Influence of rating, Less Delivery time, High Quality of package, Number of calls, Politeness, Freshness, Temperature, Good Taste, Good Quantity և Output (target փոփոխական):

# Տվյալների նախապատրաստում (Data Preprocessing)
- կատեգորիկ տվյալների վերափոխում
- կրկնվող տողերի հեռացում
- բացակայող արժեքների հեռացում

# Մոդելներ և արդյունքներ

1. Լոգիստիկ ռեգրեսիա
2. Random Forest
3. SVM
4. Gradient Boosting

   
__Մոդելների համեմատություն__

| Մոդել | Միջին F1-score	 | Դիտողություններ | 
|----------|----------|----------|
|Logistic Regression| <div align="center">0.79    |Չի կանխագուշակում դժգոհ հաճախորդներին|
|Random Forest| <div align="center">0.93    | Լավագույն մոդելը |
|SVM| <div align="center">0.77    | Վատագույն մոդելը|
|Gradient Boosting| <div align="center">0.89    | Կրկին լավ մոդել, որը կայուն է |

# Եզրակացություն
- Նախընտրելի է օգտագործել Random Forest մեթոդը լավագույն արդյունքը ստանալու համար: 
- Լավ կաշխատի նաեւ Gradient Boosting մեթոդը: 
- Իսկ SVM եւ Logistic Regression մեթոդները համեմատաբար վատ են կանխագուշակում:
