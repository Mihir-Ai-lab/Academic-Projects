# **Introduction**

## Company Introduction - Accredian Telecom

Accredian Telecom is a prominent player in the telecommunications industry, delivering a wide array of services to millions of users. In an era of heightened industry competition, Accredian Telecom acknowledges the paramount importance of personalization and customization to maintain its competitive edge. With this vision in mind, the company seeks to leverage the extensive behavioral data generated daily by mobile devices in India. By harnessing this data, Accredian Telecom aims to assist its clients in gaining deeper insights into their target audiences and improving their interactions.

## Project Overview

The primary objective of this project is to develop a comprehensive dashboard capable of providing profound insights into users' demographic characteristics, mobile usage patterns, geolocation data, and mobile device properties. Through meticulous analysis of these datasets, the dashboard will furnish valuable insights to millions of developers and brand advertisers, enabling data-driven marketing endeavors. By understanding user preferences, behaviors, and demographics, this dashboard will underpin the creation of highly relevant marketing strategies, leading to more effective campaigns and improved audience engagement.

## Objectives

The central objectives of this project encompass:

- **Acquiring and preparing essential data for analysis:** This project involves retrieving and processing three primary datasets: demographic information (including user gender and age), mobile device properties (brand and model), and event data (capturing mobile usage, geolocation, and timestamps).

- **Performing demographic analysis based on user gender and age segments:** This analysis will delve into the distribution of Accredian Telecom users across gender and age segments, offering insights into the composition of the user base and uncovering demographic trends or patterns.

- **Conducting geographical analysis to discern the distribution of Accredian Telecom users in specific states:** By scrutinizing user geolocation data, this project will uncover how Accredian Telecom users are distributed across different states. This analysis will illuminate user concentration in specific regions, providing a clearer understanding of the company's reach.

- **Analyzing phone brand preferences among Accredian Telecom users:** This project will explore the distribution of phone brands among Accredian Telecom users, shedding light on the popularity of different brands within the user base and uncovering brand preferences or correlations with demographic factors.

- **Exploring user activity patterns, including the hourly distribution of phone calls and user activity over time:** The project will delve into user activity patterns by examining the hourly distribution of phone calls and analyzing user activity across time periods. This analysis will yield valuable insights into user engagement patterns, peak usage hours, and potential trends in mobile usage behavior.

- **Summarizing findings, providing actionable insights, and suggesting recommendations for further analysis:** The project will synthesize key findings from various analyses conducted, offering actionable insights to marketers and developers, aiding in strategy optimization. Additionally, the project will propose further analysis directions to extract deeper insights.

Through the attainment of these objectives, the project endeavors to empower Accredian Telecom and its clients with a robust data-driven dashboard that supports targeted marketing, audience comprehension, and enhanced user engagement.

<p align="center"><img src="https://raw.githubusercontent.com/Mihir-Ai-lab/Academic-Projects/main/Images/Analytics.gif"></p>

---
# **Data Acquisition & Description**

This step entails acquiring the necessary datasets for our analysis. The data is collected from mobile apps utilizing Accredian Telecom services. 

The data schema comprises the following tables:

- **gender_age_train:** This table contains device information along with user gender, age, and age group.
- **phone_brand_device_model:** This table includes device IDs, brands, and models. Please note that some brands are in Chinese.
- **events_data:** This table logs events when a user employs a mobile device on an Accredian Telecom network. Each event is associated with an event ID, location (latitude/longitude), and reflects the frequency of mobile usage and timestamps (when the user is using the mobile).

---
# **Summary of Findings**

For a comprehensive analysis of the data, please refer [here](https://github.com/Mihir-Ai-lab/Academic-Projects/blob/main/EDA%20Projects/Accredian%20Telecom/Accredian%20Telecom.ipynb "here").

---
# **Actionable Insights & Recommendations**

### 1. Enhancing Personalization and Targeted Marketing

Accredian Telecom can capitalize on demographic analysis to tailor marketing campaigns and promotions to specific gender and age segments. The analysis reveals that males constitute a larger portion of the user base compared to females, with 35,146 males in the population dataset and 2,493 males in the sample dataset. By comprehending these demographics, Accredian Telecom can design targeted advertisements that resonate with each group's preferences and interests. For instance, marketing campaigns aimed at male users can emphasize technological features and gaming capabilities, while campaigns for female users can spotlight camera capabilities and lifestyle features.

Additionally, the geographical analysis highlights key regions with a high concentration of Accredian Telecom users, including Madhya Pradesh, Chhattisgarh, Uttaranchal, Jammu and Kashmir, Goa, and Nagaland. Identifying these regions enables Accredian Telecom to implement localized advertising efforts to maximize brand exposure and engagement. This localized approach may involve collaborations with local influencers or event sponsorships in these areas to enhance brand awareness and connect with the target audience.

Furthermore, the phone brand analysis reveals that Xiaomi, Samsung, and Huawei are the top phone brands preferred by AT users nationwide. Accredian Telecom can capitalize on these findings by cultivating partnerships or offering exclusive deals with these popular phone brands. Collaboration with these brands can enhance customer acquisition and retention, providing access to new features and technologies that align with user preferences.

Accredian Telecom can employ demographic analysis to personalize marketing campaigns for specific gender and age segments. Understanding the distribution of AT users by gender and age segments enables the design of targeted advertisements aligned with each group's preferences.

### 2. Improving User Experience and Engagement

Analyzing user activity patterns is pivotal for enhancing user experience and engagement. The hourly distribution of phone calls among AT users in selected states reveals peak usage periods, guiding resource allocation and service optimization. Identifying these peak usage hours empowers Accredian Telecom to optimize service availability and customer support during these periods, ensuring a seamless user experience. For instance, additional customer support staff can be deployed during peak hours to minimize wait times and enhance customer satisfaction.

To further boost user engagement, Accredian Telecom can contemplate the introduction of interactive features or gamification elements within their app. These features encourage users to explore various functionalities of the app, prolonging their time on the platform and fostering enjoyment and loyalty. An interactive and engaging app can bolster user retention and heighten user satisfaction.

Additionally, exploring user behavior data can unveil valuable insights for introducing new features or services aligned with user preferences and usage patterns. By scrutinizing user behavior, Accredian Telecom can pinpoint areas for improvement or identify opportunities to introduce new features that cater to evolving user needs. This data-driven approach guarantees that the company continues to offer innovative and pertinent services to its users.

- F23- is generally most active on Friday mornings at 10 o'clock.
- F24-26 is generally most active on Friday mornings at 10 o'clock.
- F27-28 is generally most active on Friday mornings at 10 o'clock.
- F29-32 is generally most active on Friday mornings at 10 o'clock.
- F33-42 is generally most active on Friday mornings at 10 o'clock.
- F43+ is generally most active on Friday mornings at 9 o'clock.
- M22- is generally most active on Friday mornings at 10 o'clock.
- M23-26 is generally most active on Friday mornings at 10 o'clock.
- M27-28 is generally most active on Friday mornings at 10 o'clock.
- M29-31 is generally most active on Friday mornings at 10 o'clock.
- M32-38 is generally most active on Friday mornings at 10 o'clock.
- M39+ is generally most active on Friday mornings at 10 o'clock.

### 3. Exploring VPN Usage and Potential Product Recommendations

The analysis of VPN usage provides insights into user privacy concerns and preferences. Accredian Telecom can leverage this analysis to comprehend the significance of data security and user privacy within its user base. To address these concerns, Accredian Telecom can contemplate partnerships with reputable VPN providers or enhancing its in-house VPN offerings. By providing secure and private connections, Accredian Telecom can instill peace of mind in users and cultivate trust with its customer base.

Additionally, Accredian Telecom should offer transparent information to users about its data handling practices. This entails elucidating how user data is collected, stored, and utilized, as well as implementing measures to ensure data security. By maintaining transparency regarding data handling practices and emphasizing its commitment to privacy and security, Accredian Telecom can foster trust and loyalty among its user base.

## 4. Collecting Data from Watches for Health Analysis

Although not covered in the analyses conducted thus far, the collection of data from smartwatches can yield valuable insights for health analysis. Smartwatches with health monitoring capabilities can track users' physical activity, heart rate, sleep patterns, and more. By aggregating and analyzing this data, Accredian Telecom can gain insights into users' health and well-being, potentially offering personalized health recommendations or services. Incorporating health-related features into the app or partnering with health-related organizations can further enhance the user experience and position Accredian Telecom as a holistic provider of telecom and health-related services.

These actionable insights and recommendations are grounded in the findings from the analyses conducted in this project. By implementing these recommendations, Accredian Telecom can refine its marketing strategies, elevate user experience and engagement, address privacy concerns, and explore opportunities in health analysis. This will contribute to the company's growth, bolster user satisfaction, and strengthen its competitive position in the telecommunications industry.

---
# **Credits**

I extend my heartfelt gratitude to the entire team: [Ekta Saroha](https://www.linkedin.com/in/ekta-saroha-73395816b), [Murali Krishna Raparthi](https://www.linkedin.com/in/muralikrishnaraparthi), [Bushra Kurikkal Madathil](https://www.linkedin.com/in/bushra-kurikkal-madathil-40b19426), [Kishori Ivaturi](https://www.linkedin.com/in/kishori-ivaturi-432330236), [Pridarshi Samrat](https://www.linkedin.com/in/pridarshi-samrat-825ab2167) and [Rinisha Bagaria](https://www.linkedin.com/in/rinisha-bagaria-434742a1) for their invaluable contributions during this project.

# **Thank you**

For more projects, please [Click Here](https://github.com/Mihir-Ai-lab/Academic-Projects/tree/main "Click Here").
