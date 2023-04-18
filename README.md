# **Insights based on Marginal and Conditional Probabilities**

---

## Product
~~~
KP281    0.444444
KP481    0.333333
KP781    0.222222
~~~

`Observations`

1. We can see that the most sold product is KP281 and least sold is KP781
2. KP281 is the most basic and cheapest of given products, hence sold the most
3. KP781 is the most advanced and most expensive product hence lesser people prefer to buy it
4. KP481 is the intermediate product sold most next to KP281.

## Gender

~~~
Gender given Product
--------------------------------------------------
P(Gender = 'Female'|Product = 'KP281'): 0.500
P(Gender = 'Female'|Product = 'KP481'): 0.483
P(Gender = 'Female'|Product = 'KP781'): 0.175
P(Gender = 'Female'|Product = 'All'): 0.422

P(Gender = 'Male'|Product = 'KP281'): 0.500
P(Gender = 'Male'|Product = 'KP481'): 0.517
P(Gender = 'Male'|Product = 'KP781'): 0.825
P(Gender = 'Male'|Product = 'All'): 0.578

Product given Gender
--------------------------------------------------
P(Product = 'KP281'|Gender = 'Female'): 0.526
P(Product = 'KP281'|Gender = 'Male'): 0.385
P(Product = 'KP281'|Gender = 'All'): 0.444

P(Product = 'KP481'|Gender = 'Female'): 0.382
P(Product = 'KP481'|Gender = 'Male'): 0.298
P(Product = 'KP481'|Gender = 'All'): 0.333

P(Product = 'KP781'|Gender = 'Female'): 0.092
P(Product = 'KP781'|Gender = 'Male'): 0.317
P(Product = 'KP781'|Gender = 'All'): 0.222
~~~

`Observations`

1. Overall approximately 58% of customers are Male and 42% of customers are female
1. KP281 is bought equally by male and female customers
1. KP481 is also bought almost equally by male and females with male customers being marginally higher
1. KP781 is the product in which we observe vast difference in the genders who bought it with male customers accounting for 82% of the customers and female customers accounting for only 18%.
1. Among female customers KP281 is preferred the most with 52% of total female customers buying it and KP781 is bought the least with only 9.2% of female customers.
1. Among male customers all the products are bought almost equally with KP281 being most bought and KP481 being least bought.


## Education

~~~
Education given Product
--------------------------------------------------
P(Education = '12'|Product = 'KP281'): 0.025
P(Education = '12'|Product = 'KP481'): 0.017
P(Education = '12'|Product = 'KP781'): 0.000
P(Education = '12'|Product = 'All'): 0.017

P(Education = '13'|Product = 'KP281'): 0.037
P(Education = '13'|Product = 'KP481'): 0.033
P(Education = '13'|Product = 'KP781'): 0.000
P(Education = '13'|Product = 'All'): 0.028

P(Education = '14'|Product = 'KP281'): 0.375
P(Education = '14'|Product = 'KP481'): 0.383
P(Education = '14'|Product = 'KP781'): 0.050
P(Education = '14'|Product = 'All'): 0.306

P(Education = '15'|Product = 'KP281'): 0.050
P(Education = '15'|Product = 'KP481'): 0.017
P(Education = '15'|Product = 'KP781'): 0.000
P(Education = '15'|Product = 'All'): 0.028

P(Education = '16'|Product = 'KP281'): 0.487
P(Education = '16'|Product = 'KP481'): 0.517
P(Education = '16'|Product = 'KP781'): 0.375
P(Education = '16'|Product = 'All'): 0.472

P(Education = '18'|Product = 'KP281'): 0.025
P(Education = '18'|Product = 'KP481'): 0.033
P(Education = '18'|Product = 'KP781'): 0.475
P(Education = '18'|Product = 'All'): 0.128

P(Education = '20'|Product = 'KP281'): 0.000
P(Education = '20'|Product = 'KP481'): 0.000
P(Education = '20'|Product = 'KP781'): 0.025
P(Education = '20'|Product = 'All'): 0.006

P(Education = '21'|Product = 'KP281'): 0.000
P(Education = '21'|Product = 'KP481'): 0.000
P(Education = '21'|Product = 'KP781'): 0.075
P(Education = '21'|Product = 'All'): 0.017

Product given Education
--------------------------------------------------
P(Product = 'KP281'|Education = '12'): 0.667
P(Product = 'KP281'|Education = '13'): 0.600
P(Product = 'KP281'|Education = '14'): 0.545
P(Product = 'KP281'|Education = '15'): 0.800
P(Product = 'KP281'|Education = '16'): 0.459
P(Product = 'KP281'|Education = '18'): 0.087
P(Product = 'KP281'|Education = '20'): 0.000
P(Product = 'KP281'|Education = '21'): 0.000
P(Product = 'KP281'|Education = 'All'): 0.444

P(Product = 'KP481'|Education = '12'): 0.333
P(Product = 'KP481'|Education = '13'): 0.400
P(Product = 'KP481'|Education = '14'): 0.418
P(Product = 'KP481'|Education = '15'): 0.200
P(Product = 'KP481'|Education = '16'): 0.365
P(Product = 'KP481'|Education = '18'): 0.087
P(Product = 'KP481'|Education = '20'): 0.000
P(Product = 'KP481'|Education = '21'): 0.000
P(Product = 'KP481'|Education = 'All'): 0.333

P(Product = 'KP781'|Education = '12'): 0.000
P(Product = 'KP781'|Education = '13'): 0.000
P(Product = 'KP781'|Education = '14'): 0.036
P(Product = 'KP781'|Education = '15'): 0.000
P(Product = 'KP781'|Education = '16'): 0.176
P(Product = 'KP781'|Education = '18'): 0.826
P(Product = 'KP781'|Education = '20'): 1.000
P(Product = 'KP781'|Education = '21'): 1.000
P(Product = 'KP781'|Education = 'All'): 0.222
~~~

`Observations`

1. People with 16 or less years of education mostly buy KP281 or KP481
1. People with 16 or more years of education mostly buy KP781 with people having >=20yrs of education buying only KP781
1. High Education level seems to be the indicator for buying advanced and expensive products


## Marital Status

~~~
MaritalStatus given Product
--------------------------------------------------
P(MaritalStatus = 'Partnered'|Product = 'KP281'): 0.600
P(MaritalStatus = 'Partnered'|Product = 'KP481'): 0.600
P(MaritalStatus = 'Partnered'|Product = 'KP781'): 0.575
P(MaritalStatus = 'Partnered'|Product = 'All'): 0.594

P(MaritalStatus = 'Single'|Product = 'KP281'): 0.400
P(MaritalStatus = 'Single'|Product = 'KP481'): 0.400
P(MaritalStatus = 'Single'|Product = 'KP781'): 0.425
P(MaritalStatus = 'Single'|Product = 'All'): 0.406

Product given MaritalStatus
--------------------------------------------------
P(Product = 'KP281'|MaritalStatus = 'Partnered'): 0.449
P(Product = 'KP281'|MaritalStatus = 'Single'): 0.438
P(Product = 'KP281'|MaritalStatus = 'All'): 0.444

P(Product = 'KP481'|MaritalStatus = 'Partnered'): 0.336
P(Product = 'KP481'|MaritalStatus = 'Single'): 0.329
P(Product = 'KP481'|MaritalStatus = 'All'): 0.333

P(Product = 'KP781'|MaritalStatus = 'Partnered'): 0.215
P(Product = 'KP781'|MaritalStatus = 'Single'): 0.233
P(Product = 'KP781'|MaritalStatus = 'All'): 0.222
~~~

`Observations`

1. For products KP281 and KP481 60% of the people were Partnered and 40% were single. KP781 had similar distribution with ~57% Partnered and ~43% single.
1. Overall ~60% customers were partnered and ~40% were single which means that Married people are more likely to buy these products.
1. Among Partnered people, KP281 was preferred most at ~45%, then KP481 was preferred at ~33%, then KP781 was preferred at ~22%. These numbers were quite similar for single customers.


## Usage

~~~
Usage given Product
--------------------------------------------------
P(Usage = '2'|Product = 'KP281'): 0.237
P(Usage = '2'|Product = 'KP481'): 0.233
P(Usage = '2'|Product = 'KP781'): 0.000
P(Usage = '2'|Product = 'All'): 0.183

P(Usage = '3'|Product = 'KP281'): 0.463
P(Usage = '3'|Product = 'KP481'): 0.517
P(Usage = '3'|Product = 'KP781'): 0.025
P(Usage = '3'|Product = 'All'): 0.383

P(Usage = '4'|Product = 'KP281'): 0.275
P(Usage = '4'|Product = 'KP481'): 0.200
P(Usage = '4'|Product = 'KP781'): 0.450
P(Usage = '4'|Product = 'All'): 0.289

P(Usage = '5'|Product = 'KP281'): 0.025
P(Usage = '5'|Product = 'KP481'): 0.050
P(Usage = '5'|Product = 'KP781'): 0.300
P(Usage = '5'|Product = 'All'): 0.094

P(Usage = '6'|Product = 'KP281'): 0.000
P(Usage = '6'|Product = 'KP481'): 0.000
P(Usage = '6'|Product = 'KP781'): 0.175
P(Usage = '6'|Product = 'All'): 0.039

P(Usage = '7'|Product = 'KP281'): 0.000
P(Usage = '7'|Product = 'KP481'): 0.000
P(Usage = '7'|Product = 'KP781'): 0.050
P(Usage = '7'|Product = 'All'): 0.011

Product given Usage
--------------------------------------------------
P(Product = 'KP281'|Usage = '2'): 0.576
P(Product = 'KP281'|Usage = '3'): 0.536
P(Product = 'KP281'|Usage = '4'): 0.423
P(Product = 'KP281'|Usage = '5'): 0.118
P(Product = 'KP281'|Usage = '6'): 0.000
P(Product = 'KP281'|Usage = '7'): 0.000
P(Product = 'KP281'|Usage = 'All'): 0.444

P(Product = 'KP481'|Usage = '2'): 0.424
P(Product = 'KP481'|Usage = '3'): 0.449
P(Product = 'KP481'|Usage = '4'): 0.231
P(Product = 'KP481'|Usage = '5'): 0.176
P(Product = 'KP481'|Usage = '6'): 0.000
P(Product = 'KP481'|Usage = '7'): 0.000
P(Product = 'KP481'|Usage = 'All'): 0.333

P(Product = 'KP781'|Usage = '2'): 0.000
P(Product = 'KP781'|Usage = '3'): 0.014
P(Product = 'KP781'|Usage = '4'): 0.346
P(Product = 'KP781'|Usage = '5'): 0.706
P(Product = 'KP781'|Usage = '6'): 1.000
P(Product = 'KP781'|Usage = '7'): 1.000
P(Product = 'KP781'|Usage = 'All'): 0.222
~~~

`Observations`

1. People with usage <= 4 times a week are most likely to buy either KP281 or KP481.
1. People with usage >=4 times a week are most likely to buy KP781
1. People who reported their usage >= 6 times a week are most certain to buy KP781
1. People who reported their usage <= 3 times a week are almost certain to never buy KP781
1. People most likely to buy KP481 use the product <= 4 time a week.


## Fitness

~~~
Fitness given Product
--------------------------------------------------
P(Fitness = '1'|Product = 'KP281'): 0.013
P(Fitness = '1'|Product = 'KP481'): 0.017
P(Fitness = '1'|Product = 'KP781'): 0.000
P(Fitness = '1'|Product = 'All'): 0.011

P(Fitness = '2'|Product = 'KP281'): 0.175
P(Fitness = '2'|Product = 'KP481'): 0.200
P(Fitness = '2'|Product = 'KP781'): 0.000
P(Fitness = '2'|Product = 'All'): 0.144

P(Fitness = '3'|Product = 'KP281'): 0.675
P(Fitness = '3'|Product = 'KP481'): 0.650
P(Fitness = '3'|Product = 'KP781'): 0.100
P(Fitness = '3'|Product = 'All'): 0.539

P(Fitness = '4'|Product = 'KP281'): 0.113
P(Fitness = '4'|Product = 'KP481'): 0.133
P(Fitness = '4'|Product = 'KP781'): 0.175
P(Fitness = '4'|Product = 'All'): 0.133

P(Fitness = '5'|Product = 'KP281'): 0.025
P(Fitness = '5'|Product = 'KP481'): 0.000
P(Fitness = '5'|Product = 'KP781'): 0.725
P(Fitness = '5'|Product = 'All'): 0.172

Product given Fitness
--------------------------------------------------
P(Product = 'KP281'|Fitness = '1'): 0.500
P(Product = 'KP281'|Fitness = '2'): 0.538
P(Product = 'KP281'|Fitness = '3'): 0.557
P(Product = 'KP281'|Fitness = '4'): 0.375
P(Product = 'KP281'|Fitness = '5'): 0.065
P(Product = 'KP281'|Fitness = 'All'): 0.444

P(Product = 'KP481'|Fitness = '1'): 0.500
P(Product = 'KP481'|Fitness = '2'): 0.462
P(Product = 'KP481'|Fitness = '3'): 0.402
P(Product = 'KP481'|Fitness = '4'): 0.333
P(Product = 'KP481'|Fitness = '5'): 0.000
P(Product = 'KP481'|Fitness = 'All'): 0.333

P(Product = 'KP781'|Fitness = '1'): 0.000
P(Product = 'KP781'|Fitness = '2'): 0.000
P(Product = 'KP781'|Fitness = '3'): 0.041
P(Product = 'KP781'|Fitness = '4'): 0.292
P(Product = 'KP781'|Fitness = '5'): 0.935
P(Product = 'KP781'|Fitness = 'All'): 0.222
~~~

`Observations`

1. Among people who rated their fitness level as '5' 93.5 % people bought KP781.
1. Among people who bought KP781, 72.5% people rated their fitness level as '5'. We can say that fitness levels directly relate to buying advanced products.
1. People who rated their fitness level '<3' mostly bought KP281 or KP481
1. Of the people who rated their fitness levels as 1,2 or 3 ~50% bought KP281 and ~50% bought KP481


## Age Group

~~~
Age_Group given Product
--------------------------------------------------
P(Age_Group = '18-25'|Product = 'KP281'): 0.425
P(Age_Group = '18-25'|Product = 'KP481'): 0.467
P(Age_Group = '18-25'|Product = 'KP781'): 0.425
P(Age_Group = '18-25'|Product = 'All'): 0.439

P(Age_Group = '25-30'|Product = 'KP281'): 0.263
P(Age_Group = '25-30'|Product = 'KP481'): 0.117
P(Age_Group = '25-30'|Product = 'KP781'): 0.325
P(Age_Group = '25-30'|Product = 'All'): 0.228

P(Age_Group = '30-40'|Product = 'KP281'): 0.237
P(Age_Group = '30-40'|Product = 'KP481'): 0.383
P(Age_Group = '30-40'|Product = 'KP781'): 0.150
P(Age_Group = '30-40'|Product = 'All'): 0.267

P(Age_Group = '40-50'|Product = 'KP281'): 0.075
P(Age_Group = '40-50'|Product = 'KP481'): 0.033
P(Age_Group = '40-50'|Product = 'KP781'): 0.100
P(Age_Group = '40-50'|Product = 'All'): 0.067

Product given Age_Group
--------------------------------------------------
P(Product = 'KP281'|Age_Group = '18-25'): 0.430
P(Product = 'KP281'|Age_Group = '25-30'): 0.512
P(Product = 'KP281'|Age_Group = '30-40'): 0.396
P(Product = 'KP281'|Age_Group = '40-50'): 0.500
P(Product = 'KP281'|Age_Group = 'All'): 0.444

P(Product = 'KP481'|Age_Group = '18-25'): 0.354
P(Product = 'KP481'|Age_Group = '25-30'): 0.171
P(Product = 'KP481'|Age_Group = '30-40'): 0.479
P(Product = 'KP481'|Age_Group = '40-50'): 0.167
P(Product = 'KP481'|Age_Group = 'All'): 0.333

P(Product = 'KP781'|Age_Group = '18-25'): 0.215
P(Product = 'KP781'|Age_Group = '25-30'): 0.317
P(Product = 'KP781'|Age_Group = '30-40'): 0.125
P(Product = 'KP781'|Age_Group = '40-50'): 0.333
P(Product = 'KP781'|Age_Group = 'All'): 0.222
~~~

`Observations`

1. Majority of the customers are in the age group - '18-25'. Poeple in this age group are most likely to buy KP281 and KP481 and least likely to buy KP781
1. Among all age groups '18-25' is still the most likely to buy KP781
1. People in age group 40-50 preferred KP281 the most at 50%, then KP781 at 33%, then KP481 at 17%
1. People in age group 25-30 are most likely to buy KP281


## Income Group

~~~
Income_Group given Product
--------------------------------------------------
P(Income_Group = '25000-50000'|Product = 'KP281'): 0.600
P(Income_Group = '25000-50000'|Product = 'KP481'): 0.500
P(Income_Group = '25000-50000'|Product = 'KP781'): 0.125
P(Income_Group = '25000-50000'|Product = 'All'): 0.461

P(Income_Group = '50000-75000'|Product = 'KP281'): 0.400
P(Income_Group = '50000-75000'|Product = 'KP481'): 0.500
P(Income_Group = '50000-75000'|Product = 'KP781'): 0.350
P(Income_Group = '50000-75000'|Product = 'All'): 0.422

P(Income_Group = '75000-10000'|Product = 'KP281'): 0.000
P(Income_Group = '75000-10000'|Product = 'KP481'): 0.000
P(Income_Group = '75000-10000'|Product = 'KP781'): 0.450
P(Income_Group = '75000-10000'|Product = 'All'): 0.100

P(Income_Group = '100000+'|Product = 'KP281'): 0.000
P(Income_Group = '100000+'|Product = 'KP481'): 0.000
P(Income_Group = '100000+'|Product = 'KP781'): 0.075
P(Income_Group = '100000+'|Product = 'All'): 0.017

Product given Income_Group
--------------------------------------------------
P(Product = 'KP281'|Income_Group = '25000-50000'): 0.578
P(Product = 'KP281'|Income_Group = '50000-75000'): 0.421
P(Product = 'KP281'|Income_Group = '75000-10000'): 0.000
P(Product = 'KP281'|Income_Group = '100000+'): 0.000
P(Product = 'KP281'|Income_Group = 'All'): 0.444

P(Product = 'KP481'|Income_Group = '25000-50000'): 0.361
P(Product = 'KP481'|Income_Group = '50000-75000'): 0.395
P(Product = 'KP481'|Income_Group = '75000-10000'): 0.000
P(Product = 'KP481'|Income_Group = '100000+'): 0.000
P(Product = 'KP481'|Income_Group = 'All'): 0.333

P(Product = 'KP781'|Income_Group = '25000-50000'): 0.060
P(Product = 'KP781'|Income_Group = '50000-75000'): 0.184
P(Product = 'KP781'|Income_Group = '75000-10000'): 1.000
P(Product = 'KP781'|Income_Group = '100000+'): 1.000
P(Product = 'KP781'|Income_Group = 'All'): 0.222
~~~

`Observations`

1. Among people with income <50000, KP281 is most popular and most liekly to be bought by this group.
1. People with income > 75000 have never bought KP281 or KP481, they only buy KP781
1. KP481 is equally likely to be bought by group 25000-50000 and 50000-75000.


## Miles Range

~~~
Miles_Range given Product
--------------------------------------------------
P(Miles_Range = '20-50'|Product = 'KP281'): 0.150
P(Miles_Range = '20-50'|Product = 'KP481'): 0.083
P(Miles_Range = '20-50'|Product = 'KP781'): 0.000
P(Miles_Range = '20-50'|Product = 'All'): 0.094

P(Miles_Range = '50-100'|Product = 'KP281'): 0.625
P(Miles_Range = '50-100'|Product = 'KP481'): 0.650
P(Miles_Range = '50-100'|Product = 'KP781'): 0.200
P(Miles_Range = '50-100'|Product = 'All'): 0.539

P(Miles_Range = '100-200'|Product = 'KP281'): 0.225
P(Miles_Range = '100-200'|Product = 'KP481'): 0.250
P(Miles_Range = '100-200'|Product = 'KP781'): 0.675
P(Miles_Range = '100-200'|Product = 'All'): 0.333

P(Miles_Range = '200-300'|Product = 'KP281'): 0.000
P(Miles_Range = '200-300'|Product = 'KP481'): 0.017
P(Miles_Range = '200-300'|Product = 'KP781'): 0.100
P(Miles_Range = '200-300'|Product = 'All'): 0.028

P(Miles_Range = '300+'|Product = 'KP281'): 0.000
P(Miles_Range = '300+'|Product = 'KP481'): 0.000
P(Miles_Range = '300+'|Product = 'KP781'): 0.025
P(Miles_Range = '300+'|Product = 'All'): 0.006

Product given Miles_Range
--------------------------------------------------
P(Product = 'KP281'|Miles_Range = '20-50'): 0.706
P(Product = 'KP281'|Miles_Range = '50-100'): 0.515
P(Product = 'KP281'|Miles_Range = '100-200'): 0.300
P(Product = 'KP281'|Miles_Range = '200-300'): 0.000
P(Product = 'KP281'|Miles_Range = '300+'): 0.000
P(Product = 'KP281'|Miles_Range = 'All'): 0.444

P(Product = 'KP481'|Miles_Range = '20-50'): 0.294
P(Product = 'KP481'|Miles_Range = '50-100'): 0.402
P(Product = 'KP481'|Miles_Range = '100-200'): 0.250
P(Product = 'KP481'|Miles_Range = '200-300'): 0.200
P(Product = 'KP481'|Miles_Range = '300+'): 0.000
P(Product = 'KP481'|Miles_Range = 'All'): 0.333

P(Product = 'KP781'|Miles_Range = '20-50'): 0.000
P(Product = 'KP781'|Miles_Range = '50-100'): 0.082
P(Product = 'KP781'|Miles_Range = '100-200'): 0.450
P(Product = 'KP781'|Miles_Range = '200-300'): 0.800
P(Product = 'KP781'|Miles_Range = '300+'): 1.000
P(Product = 'KP781'|Miles_Range = 'All'): 0.222
~~~

`Observations`

1. People who ran more than 300 miles bought only KP781
1. People who ran more than 200 miles never bought KP281
1. People who ran 200-300 miles bought KP781 80% of the time and KP481 20% of the time and never bought KP281
1. Among people who ran 100-200 miles, KP481 is likely to be bought 25% times and KP281 is likely to be bought 30% times and KP781 is likely to be bought 45* of the times.


# **Recommendations**
---

1. In *KP781* segment there is potential to attract more female customers. We have seen that higher income, higher usage and people who ran more miles is positively related to buying *KP781*. Females who match this criteria can be advertised this product.
2. Two new product tiers can be introduced *KP381* and *KP581*
 >   - KP381 will be below KP481 in terms of price and features
 >   - KP581 will be below KP781 in terms of price and features
    - These new tier of products can be used to cross sell between various income groups depending on whether they want to spend more or less
    - It will also give customers more options to buy matching their needs thus increasing overall revenue.
3. People with >16 years of education bought top tier product but overall numbers were low, people with higher years of education can be advertised with top-tier products
4. A mid income person who is male with high fitness rating tends to buy top tier KP781. A female customer with similar characteristics tends to buy mid tier KP481. This presents a huge potential opportunity to upsell KP781 to female customers with matching characteristics as they'll most likely buy the product.
5. People who ran between 100-300 miles used mostly *KP481*, they are likely to buy *KP781* given the distance covered by them.