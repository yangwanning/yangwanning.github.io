---
date: 2017-01-1
published: true
sitemap: false
title: 'Chronic Kidney Disease: Factor Analysis' 
description: "Data Analytics and Modeling"
categories: app, ux, mobile
disciplines: Feature Selection, Imbalanced Lable, Classification
media: Mobile App
ownership:
client: Butterfly
time_period: 2020
thumbnail: "/projects/CKD/ckd-theme.jpg"
accent:
  color:
  inverted:
website:
  button_text: Visit the site
  url: https://github.com/yangwanning/CKD-Factor-Analysis

intro:
  Chronic kidney disease has become a serious public health issue around the world. The overall prevelance of CKD in the general population is approximately 14% and is still increasing. The high growth of CKD can result in considerable healthcare cost and impose restrictions on many patients' daily livings. One way to reduce the economic burden of CKD would be <b>early intervention</b>, with <b>early diagnosis and treatment</b>, it is possible to slow the progression of CKD.


  Therefore, <b>our target</b> is to help healthcare organization to identify the individuals with high risk of CKD. In order to achieve it, <b>our approach</b> is to collect public data and use them to build the final predictive model. 


  Considering the survey costs and survey quality, we want to keep our survey process simple but effective, that is, to ask public only several determined questions. According to previous research, CKD can be cuased by different risk factors such as race, gender, age, and family history. Moreover, smoking, obesity, hypertension, and diabetes mellitus can also lead to CKD. So <b>our challenge</b> is how to identify the most important risk factor among all possible information. 



  <b> This notebook covers:</b><br>
  1. Data Exploration<br>
  2. Feature Selection by Bayes Probability and Random Forest<br>
  3. Data Modeling and Evaluation<br>



  <b>Conclusions:</b>

  From our analysis, "Age" is a highly important factor, indicating that elderly people are more prone to develop CKD. Beside, factors such as "Hypertension", "Diabetes", "Anemia", "Stroke" are also likely to lead to kidney disease. Other factors like "Smoker", "Weight" and some other healthy issues such as "CHF (Congestive Heart Failure)", "CVD (cardiovascular disease)" could also constitute risks.

  In order to make our survey easy for interviewees to conduct, we decided to chose 6 strongest risk factors as our survey questions. In this way, our final predictive model can be more simple and interpretable.


  <b>Recommendations:</b>

  Finally, we hope people can pay more attention to their health as well as their families. Chronic kidney disease may not become apparent until your kidney function is significantly impaired. Thus, taking regular screenings for CKD is necessary if you are at high risk (check our analysis), especially for elderly people, and controlling conditions like diabetes (check our analysis) can also help.

    

<!-- content_layout:
  - section_layout: 1col
    images:
      - caption: Main functional tabs
        description: 'Navigation'
        url: '/projects/butterfly/butterfly-main-navigation.jpg'
        width:
        height:

  - section_layout: 1col
    images:
      - caption: Public profile media
        description: 'Profile screens'
        url: '/projects/butterfly/butterfly-profile.jpg'
        width:
        height:

  - section_layout: 1col
    images:
      - caption: Onboarding
        description: 'Onboarding'
        url: '/projects/butterfly/butterfly-onboarding.jpg'
        width:
        height:

  - section_layout: 1col
    images:
      - caption: Chat
        description: 'Chat'
        url: '/projects/butterfly/butterfly-chat.jpg'
        width:
        height:
---
 -->