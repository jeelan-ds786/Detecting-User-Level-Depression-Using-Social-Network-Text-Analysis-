# Detecting-User-Level-Depression-using-social-network-Text-Analysis-
Depression detection using an individual's surrounding network.

<hr>

<br><br>

## 1) Abstract :

  * Recent research has suggested a link between heavy social media use and elevated depression. One of the most prevalent mental health issues in the world is depression. A doctor typically makes a diagnosis of depression based on patient surveys and self-reports regarding their mental health. These treatments depend heavily on the patient's mental state, and depressed people frequently resist getting help. People can communicate their sentiments and opinions with friends and family using social media. There is a chance to create new frameworks for detecting people at risk for depression given the abundance of data in social networks. This framework could also help institutions and medical professionals to understand the symptoms and behaviors of depression. With this in mind, we suggest a big data analytics approach for identifying depression in users of social networks. In addition to semantic and syntactic features, it focuses on useful qualities for modeling user intention. The underlying driving force behind a user's actions on a social network can be seen in their intent. The framework also models the impact of friends on a user's mental state. It is thought that the actions of the user's friends have an impact on them. We analyze the framework's performance using a sizable real-world dataset that we collected from Facebook, for identifying depression at the user level in social networks.

<hr>


## 2) Dataset  

  * The Big Five personality traits, also known as the five-factor model (FFM) and the OCEAN model, is a taxonomy, or grouping, for personality traits. When factor analysis (a statistical technique) is applied to personality survey data, some words used to describe aspects of personality are often applied to the same person. For example, someone described as conscientious is more likely to be described as "always prepared" rather than "messy". This theory is based therefore on the association between words but not on neuropsychological experiments. This theory uses descriptors of common language and therefore suggests five broad dimensions commonly used to describe the human personality and psyche. (wikipedia)[click here](1.Dataset) ..

<hr>

## 3) Data Preprocessing 

 * Data preprocessing is an important step in the data mining process that involves cleaning and transforming raw data to make it suitable for analysis. Some common steps in data preprocessing include:

  `Data Cleaning` : This involves identifying and correcting errors or inconsistencies in the data, such as missing values, outliers, and duplicates. Various techniques can be used for data cleaning, such as imputation, removal, and transformation.

  `Data Integration` : This involves combining data from multiple sources to create a unified dataset. Data integration can be challenging as it requires handling data with different formats, structures, and semantics. Techniques such as record linkage and data fusion can be used for data integration.。[click here](2.Data_Preprocessing)..

<hr>

## 4) Seven Model Implementation

 * 田中くんと佐藤さんは、高校3年間、恋人として仲良く過ごしました。二人は一緒に学校に通い、一緒に遊び、一緒に勉強しました。二人はいつも一緒にいて、お互いに支え合って、成長していきました。

ある日、田中くんは佐藤さんにプロポーズしました。佐藤さんは喜んでプロポーズを受け入れました。二人は結婚式を挙げ、幸せな家庭を築きました。[click here](3.Seven_Machine_Learning_Model_Implementation) ..

<hr>

## 5) Intentional Model 

別れの時 田中くんと佐藤さんは、結婚して5年後、田中くんが海外に転勤することになりました。佐藤さんは仕事が忙しく、一緒に海外に行くことができませんでした。二人は遠距離恋愛をすることになりました。

遠距離恋愛は大変でしたが、二人は互いに愛し合っていました。月に一度は会うようにしていました。二人は遠距離恋愛も上手くいっていました。[click here](5.Intentional_Model) ..

<hr>

## 6) Path Approach

結婚生活 田中くんと佐藤さんは、結婚して10年後、二人に子供ができました。子供は女の子で、名前はさくらとつけました。さくらは二人の宝物でした。

田中くんと佐藤さんは、さくらを大切に育てました。さくらは元気で明るい子に育ちました。 田中くんと佐藤さんは、さくらの成長を見守りながら、幸せな結婚生活を送りました。

おわりに 田中くんと佐藤さんは、50年連れ添って、幸せな人生を送りました。二人は老夫婦になっても、お互いに愛し合っていました。田中くんと佐藤さんの愛は、永遠に続きました。[click here](6.Path_Approach)..

<hr>

## 7) Tableau Visualization

  * Tableau dashboards are highly interactive, allowing users to explore data in a variety of ways. Users can zoom in and out of data, filter data, and create custom visualizations. This makes it easy to find the insights you're looking for. Tableau dashboards are secure, with a variety of security features to protect your data. You can control who has access to your dashboards, and you can encrypt your data to keep it safe. Here we created a dashboard to analyze the Big5 traits among a network and a social metrics visualization dashboard [click here](Tableau_visualization)
<hr>

## 8) Conclusion :

  * In order to give mental health professionals a tool for tracking depressive behaviors of those at risk for depression, the study offered a machine learning-based framework for depression diagnosis. The proposed framework integrates user intention models and social influence scores to improve the prediction of the performance of currently used depression detection techniques.
  * Without relying simply on questionnaires, the framework can determine users' mental states by considering both social-level and user-level data. This makes it a valuable tool for clinicians in supporting better depression detection and follow-up treatment plans. Status updates by Facebook users are first preprocessed.
  * Then the preprocessed data are mapped to O C E A N traits.7 Machine Learning techniques: KNN, SVM, Random Forest, Baseline, Logistic Regression, Neural networks, and CART are implemented for the ‘my personality’ dataset. The statistical metrics for each model are compared and the results are analyzed. Intention models such as the Shortest path and User intentional model are computed through network graphs and the influenced scores are calculated using speech acts. Statistical measures for the user intention model are visualized.


<hr>



## 9) Future Works :

  * Future work will focus on enhancing our social influence scores by taking into account the user’s online status updates. We can explore the influence of friends further and possibly generate more accurate social influence scores by looking at the topic level for every user's status updates. Additionally, we only took into account one intention type per update state in this study. We will look into the possibility of representing an update status as the blend of intention types. This will provide fresh insight into the motivation behind user-posted status updates.

<hr>



## 10) Reference :

[1] Yang, X., McEwen, R., Ong, L. R., & Zihayat, M. (2020). A big data analytics
framework for detecting user-level depression from social networks.
International Journal of Information Management, 54, 102141.

[2] P. Adamopoulos, A. Ghose, V. Todri The impact of user personality traits on word
of mouth: Text-mining social media platforms.Information Systems Research, 29 (3)
(2018), pp. 612-640




