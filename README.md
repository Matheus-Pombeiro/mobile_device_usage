# Mobile Device Usage

## 1. Introduction

<p align='justify'>In the last few years the usage of mobile devices grew considerably. Big companies invest a lot of money to develop apps and solutions for mobile users, because they generate a good financial return to these companies. Nowadays, most web users usually use their smartphones to access websites and mobile apps. There are nice business ideas operating in the “mobile world”, like startups and big techs. Many traditional banking institutions had to adapt to this new market, as a new business model focused on digital use has emerged. These digital banks are called “fintechs”.</p>

<p align='justify'>So, in summary, mobile devices have an important role in the current scenario. They can be used for several purposes, such as fun, health, work, education, etc. And this project was developed to analyze a <a href="https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset" target="_blank" rel="noopener noreferrer">dataset</a> about mobile device usage from Kaggle. This project was developed using Pandas to treat the data and to plot charts to analyze them.</p>

### 1.1 Analysis points

<p align='justify'>Through this project some questions will be answered. Such as:</p>

<ul>
  <li>What’s the preferred device model? And which operating system this device uses? How can this impact the tech market?</li>
  <li>Are there more men or women using mobile devices? Is the difference big or small? Why?</li>
  <li>What’s the battery drain (min/day) mean and its standard deviation according to the preferred device model? And how can this impact the environment?</li>
  <li>Do men usually spend more time using mobile devices than women? Or do women use them more? Why?</li>
  <li>What’s the maximum data usage (MB/day) and their relation with the number of apps installed? For what reason could a person use so much data per day?</li>
  <li>What’s the mean of age among the users? Who are the oldest and youngest people? Who spends more time using mobile devices, the oldest or the youngest person? And what operating system do they prefer?</li>
  <li>Who has the biggest and smallest user behavior class? Are they men or women?</li>
</ul>

## 2. Exploring the data

### 2.1 Preferred device model and operating system

<p align='justify'>About the preferred device and operating system (OS), there is a tie between Xiaomi Mi 11 and iPhone 12. The first is based on the Android OS and the second uses the IOS, which is only used by Apple smartphones. There are one hundred and forty-six people using each device. But there are other devices analyzed in this database, like Google Pixel 5, OnePlus 9 and Samsung Galaxy S21, which belong to other companies.</p>

<div align="center">
  <img src="assets/charts/total_of_devices.png" alt="Total of Devices chart"/>
</div>
<br>

<p align='justify'>Through the graph it’s possible to see the usage difference among the smartphones analyzed. The Google Pixel 5 device reached a small difference in comparison to its competitors. Even so, the Apple and Xiaomi’s devices have a more present usage than the others, which includes the Samsung one.</p>

<p align='justify'>According to the <a href="https://www.globaldata.com/companies/top-companies-by-sector/technology-media-and-telecom/global-consumer-electronics-companies-by-market-cap/#:~:text=The%20United%20States%2Dbased%20Apple,increase%20of%207.8%25%20over%20FY2021." target="_blank" rel="noopener noreferrer">Global Data</a> website, Apple is the current second largest electronics company and Samsung is the sixth one. However Xiaomi, which isn’t in the top ten, could compete against them.
</p>

<p align='justify'>But why did this happen? Apple and Xiaomi are both electronics companies, but they have different business rules and possibly different goals. In some countries, where products from both companies are sold, the public who consumes the Apple devices is different from the public who consumes the Xiaomi ones. Nowadays, smartphones are indispensable tools, but not many people can buy an expensive device, even knowing about its quality. So, some people prefer to buy a cheappier smartphone. Of course, the popularity of a product can be a big influence on the public mind, like a property which causes impact in a social way, status, for example.</p>

<p align='justify'>And what kind of impacts can this cause on the market? Well, knowing about the competitive power between the two companies, Apple and Xiaomi, and the fact that, even Xiaomi was founded later than its competitor, the Chinese company is more present in some people's choices, it can grow and take a bigger piece of the market in the following years. Although companies like Samsung, which produced the lesser smartphone used and analyzed in this dataset, should analyze their enemies and their strengths and weaknesses, planning some strategies to compete by a bigger user public.</p>

<p align='justify'>About the Apple status, this company is well positioned in the tech market and, since its foundation, Apple has been building customer loyalty all over the world. Some people only use Apple’s devices and don’t have the intention to switch to other brands. Nevertheless, Xiaomi, Samsung and the other electronic companies are still a threat to Apple, because every day new technologies (devices, software applications and solutions) are developed by several companies, which can have the same interests of Apple and different ones, too.</p>

<p align='justify'>In some cases, trade disputes are influenced by governments. Apple is an American company, Xiaomi is a Chinese one and Samsung is a South Korean one. The US and China have shown competitiveness in the past, so this commercial fight among the companies can be influenced by political powers.</p>

### 2.2 Gender which uses more mobile devices

<p align='justify'>The dataset analyzed brings gender data and enables the analysis about which gender, male or female, is using more mobile devices. There are some factors which can influence this aspect, such as the professional environment, community, customs and religion where these users are involved. The financial and educational capacities of each user can determine the opportunities of their mobile device usage behavior as well.</p>

<p align='justify'>Looking at the next graph, it’s possible to see the difference between the number of male and female users. The dataset indicates a bigger number of men using mobile devices than women. Although, the difference can be considered small because there is a kind of balance between them.</p>

<div align="center">
  <img src="assets/charts/gender_number.png" alt="Gender Number chart"/>
</div>
<br>

<p align='justify'>Even so, the difference keeps there. Why? As it was described below, there are several factors which can influence this result, and a big one comes from social media usage. According to the <a href="https://www.oberlo.com/statistics/social-media-usage-by-gender" target="_blank" rel="noopener noreferrer">Oberlo</a> website, there is a study about this matter, which points out the fact that there are more men using social media than women.</p>

<p align='justify'>Nowadays, social media are powerful tools used not only by common users, but by commercial companies, religious and governmental institutions and non-governmental organizations (NGOs). Social media are present all over the world and can be useful in different manners, like fun, chat, news, education, marketing, health, politics, etc.</p>

<p align='justify'>There can be other reasons for this difference in the number of users between men and women. However, a more specialized research should be applied to explore the possibilities.</p>
