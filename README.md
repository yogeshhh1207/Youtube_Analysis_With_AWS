# Youtube_Analysis_With_AWS
The innovative project aims to securely manage, streamline, and perform insightful analysis on a vast collection of structured and semi-structured YouTube video data, leveraging video categories and trending metrics.

This project offers numerous opportunities to answer key questions and derive valuable insights to enhance viewership on YouTube. Here are some examples of the questions that can be answered using the project:

1. Which video categories receive the highest engagement and viewership?

   By analyzing the structured and semi-structured data, we can identify the most popular video categories on YouTube. This information enables the organization to focus on creating and promoting content that aligns with these categories, thereby increasing viewership.
2. What are the trending metrics associated with successful videos?

   By examining trending metrics such as views, likes, comments, and shares, the project can uncover patterns and characteristics of successful videos. This knowledge can guide content creation strategies and help the organization produce compelling videos that resonate with the audience, ultimately boosting viewership.
4. How does viewership vary across different demographics and regions?

   By leveraging the available data, the project can provide insights into the demographic composition and regional preferences of YouTube viewers. This information helps tailor content to specific target audiences and allows the organization to create region-specific promotional campaigns, leading to increased viewership.
6. Which timeframes and scheduling patterns result in higher viewership?

   Analyzing data on viewership patterns over different timeframes, such as days of the week or specific hours, can reveal optimal time slots for publishing and promoting videos. This knowledge allows the organization to schedule releases strategically, maximizing viewership potential.
8. How do engagement levels correlate with promotional activities or collaborations?

   By analyzing data on promotional activities, collaborations with other content creators, or external marketing efforts, the project can assess their impact on viewer engagement and subsequent viewership. This knowledge helps refine promotional strategies and optimize collaborations for enhanced visibility and viewership growth.
	
Overall, by providing actionable insights into audience preferences, video categories, trending metrics, and effective promotional strategies, this project empowers the organization to make data-driven decisions that optimize viewership on YouTube.

## Project Goals

1. Data Acquisition: Develop a robust mechanism to acquire data from diverse sources while prioritizing ethical practices, obtaining necessary permissions, and ensuring data integrity.

2. Data Transformation: Implement an Extract, Transform, and Load (ETL) system to convert raw data into a standardized format suitable for analysis, ensuring data quality and consistency.

3. Data Repository: Establish a centralized data lake to efficiently store and manage the amalgamated data from multiple sources, enabling seamless data access and effective data management.

4. Scalable Architecture: Design a scalable system capable of handling increasing data volumes, ensuring optimal performance, and efficient resource utilization.

5. Cloud Integration: Utilize secure and scalable cloud infrastructure, specifically Amazon Web Services (AWS), to leverage the benefits of cloud computing for processing and analyzing vast amounts of data.

6. Reporting and Visualization: Develop an intuitive and interactive dashboard that empowers users to explore and extract meaningful insights from the data, facilitating informed decision-making and driving organizational growth.

By focusing on these project goals, we aim to create a robust data management and analysis platform that enhances data acquisition, processing, storage, scalability, and reporting capabilities, resulting in valuable insights for our organization's growth and success on YouTube.

## Services Used

1. Stellar Storage: Amazon S3 (Simple Storage Service) has been employed as our stellar storage solution, providing limitless scalability, unparalleled data availability, robust security measures, and exceptional performance. It acts as the backbone of our data infrastructure, ensuring seamless storage and retrieval of the vast YouTube video dataset.

2. Guardians of Access: AWS IAM (Identity and Access Management) has been our unwavering guardian, enabling us to manage access to various AWS services and resources with utmost security and precision. It empowers us to enforce fine-grained access controls, ensuring that only authorized personnel can interact with the project's data and infrastructure.

3. Data Alchemist: AWS Glue, our trusty data integration service, acts as an ingenious alchemist, effortlessly discovering, preparing, and blending diverse data sources for analytics, machine learning, and application development. Its serverless nature and intelligent data cataloging capabilities streamline the data transformation process, paving the way for insightful analysis.

4. Serverless Sorcerer: AWS Lambda, our mystical serverless computing service, conjures the magic of running code without the hassle of managing servers. It effortlessly orchestrates the processing tasks within our project, executing functions and workflows in a cost-effective and scalable manner, leaving us free to focus on extracting valuable insights from the data.

5. Athena, the Query Virtuoso: AWS Athena, our query virtuoso, allows us to effortlessly explore and analyze the YouTube video data residing in Amazon S3. With Athena's interactive query service, we can unleash the power of queries and dive deep into the data without the need for data loading or complex setup, fueling our analytical pursuits.

6. Enlightening Insights: QuickSight, our enlightened business intelligence (BI) service, serves as the insights within our project. Powered by machine learning, QuickSight provides scalable and embeddable BI capabilities, illuminating the patterns, trends, and visualizations hidden within the YouTube video data. It empowers decision-makers with actionable information, driving strategic growth and success.

With this impressive ensemble of services, our project harnesses the capabilities of cutting-edge technologies, ensuring robust data management, secure access controls, seamless data integration, serverless computing, powerful query capabilities, and enlightening business intelligence, all orchestrated harmoniously to unlock the true potential of YouTube video data.

## Dataset Used

This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the US, GB, DE, CA, and FR regions (USA, Great Britain, Germany, Canada, and France, respectively), with up to 200 listed trending videos per day.
EDIT: Now includes data from RU, MX, KR, JP and IN regions (Russia, Mexico, South Korea, Japan and India respectively) over the same time period. 
Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Reference 

Youtube: https://youtube.com/playlist?list=PLBJe2dFI4sguF2nU6Z3Od7BX8eALZN3mU

Github: https://github.com/darshilparmar/dataengineering-youtube-analysis-project

Grateful to [darshilparmar](https://github.com/darshilparmar) for such a great guidance!!
