# Amazon_Vine_Analysis

# Module 16: BIG DATA (CLOUD COMPUTING)

## Overview

The purpose of this module was to explain in detail what BIG DATA is, what constitutes Big Data, it's infrastructure as it pertains to Big Data ecosystems such as Google COLAB and Amazon Web Services (AWS) and how it may be the future of data science industries. It was a re-introduction of sorts as we all use or heard of the term "The Cloud" as it relates to computing but as ethereal as an actual cloud in the sky, most people do not have a clear understanding of it. By using Spark, Hadoop and learning NLP: Natural Language Processing, we get a clearer understanding of this concept's implementation.

## Results

NOTE: Of the 50 Datasets choices, I decided to choose "JEWELRY" due to my past experience from working at Tiffany & Co. in Hawaii and California.

* How Many Vine Member Reviews Were There?
![image](https://user-images.githubusercontent.com/101307058/183321292-9edd1880-17f9-4348-9efc-0bc1adbfd058.png)

* How Many Vine Reviews Were 5-Stars?
![image](https://user-images.githubusercontent.com/101307058/183321326-b5484b5f-e4ff-4f60-b00f-acb2c88ad6ad.png)

* What Percentage Of Vine Member Reviews Were 5-Stars?
![image](https://user-images.githubusercontent.com/101307058/183321358-0d6c74a4-184a-4e70-97e6-42d7d0cc5859.png)

* How Many Non-Vine Member Reviews Were 5-Stars?
![image](https://user-images.githubusercontent.com/101307058/183321412-d6ceabeb-c4dd-4d4f-b0ec-a514a54fc9c7.png)

* What Percentage Of Non-Vine Reviews Were 5-Stars?
![image](https://user-images.githubusercontent.com/101307058/183321458-f64109de-9e08-4687-8727-fe8c52e58fbe.png)

* How Many Non-Vine Member 5-Star Review With A Purchase Were There?
![image](https://user-images.githubusercontent.com/101307058/183321569-5f940dba-bcf6-44f5-87b7-58132a746cd6.png)

* How Many Non-Vine Member Reviews With A Purchase Were There?
![image](https://user-images.githubusercontent.com/101307058/183321593-0d4bc6f1-2895-470a-b265-1eeb1ac2fa58.png)

* What Percentage Of Non-Vine Member 5-Star Reviews With A Purchase Were There?
![image](https://user-images.githubusercontent.com/101307058/183321610-7a3e1e8a-3e3a-4fd7-94e3-0b4d18d54190.png)

## Summary
Amazon's VINE program is an invitation-only program that takes their most trusted Amazon reviewers to post opinions about products to help their fellow customers in making informed purchase decisions. Once invited, the reviewers (called "VINE VOICES") are also offered complimentary products from Amazon's participating selling partners to try out and review. Amazon does not influence or modify Vine reviews, both negative and positive as long as they comply with the company's posting guidelines. As such, the Vine program invitees need not necessarily purchase items to review them. This point needs emphasis to understand the parameters of the calculations that were made (see above). For the category I chose "JEWELRY", there does not seem to be many invited members of the VINE program or they do not purchase or are not gifted jewelry as a category to review as often as other categories. This is evidenced by the overwhelming number of the non-Vine member total reviews 7689 as compared to the VINE member total reviews numbering only 21. Both percentages of 5-STAR reviews from VINE members and non-VINE members were above 50%: 52% and 58% respectively but did not go above 60%. Even those non-VINE members who did make a purchase and gave 5-STAR reviews came in at 59%. This shows that there is no undue bias for reviews. Unlike coffee or cosmetic product offers, offering complimentary jewelry may not be cost effective for those jewelry company partners of Amazon which explains the low number of VINE member reviews for this category. Even in jewelry, there is high-end, for example diamond jewelry and low-end such as sterling silver jewelry with prices ranging from hundreds to thousands of dollars. One recommended additional analysis would be to do a review breakdown by dollar amount:

* CATEGORY 1: $0 - $300.00
* CATEGORY 2: $301.00 - $1000.00
* CATEGORY 3: ABOVE $1000.00

