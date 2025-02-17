# Sentiment-Analysis-and-Predictive-Modeling-of-Weight-Loss-Medication-Reviews

Problem Statement

Many people who suffer from obesity rely on weight loss medication to improve their health. The effectiveness of these medications vary, with different side effects and user experiences, which creates a challenge for pharmaceutical companies, health professionals and customers. Low customer satisfaction can decrease the sales and growth potential of pharmaceutical companies. Also, health professionals may struggle when it comes to recommending drugs to customers depending on their individual experiences. Moreover, some customers spend so much money on medications that may not be beneficial to them or even worsen their condition. Hence, it is important to analyze and predict customer satisfaction ratings to identify patterns that likely lead to positive or negative customer experieces. The goal of this project is to uncover these insights to guide pharmaceutical companies to improve their products, help health workers in prescribing appropriate drugs and also help consumers understand other people's experience with a particular medication before making a purchase. Ratings serve as a key indicator of customer satisfaction with the product.

Who It Affects

Customers: Depend on ratings and reviews to make informed decisions about choosing the right medication.

Pharmaceutical Companies: Use customer feedback to enhance product quality and services.

Healthcare Providers: Leverage insights to recommend the most effective treatments to patients.

Financial and Social Implications

Financial: Companies that address low ratings will be able to identify the weaknesses of their product offerings so they can improve upon them, thereby fostering customer loyalty and satisfaction and increasing sales. On the other hand, neglecting negative reviews may harm their reputation because ignoring recurring issues with their product can lead to lawsuits and product recalls.

Social: Unhappy customers may stop using the medication, potentially compromising their health. Accurately predicting and addressing low ratings can improve public trust and lead to better health outcomes.

Model Usage

Building a model to analyze large volumes of customer review data can help identify key factors influencing customer satisfaction. By doing so:

Companies can track trends in customer satisfaction over time, identify common side effects and overall user experience.

Early detection of low ratings enables prompt action to resolve complaints or enhance products.

Health professions can leverage insights from the model to understand user experience with weight loss medication so they can recommend treatments that best aligns with patient needs.

Insights from the predictions will guide product development and marketing strategies to better align with customer needs and preferences.

The model can also be integrated into reveiw platforms or health apps to aid users in making personal decisions about which drugs best suits their needs

Desired Model Performance

The model must effectively predict ratings, with a focus on identifying negative reviews or ratings to pinpoint the cause of dissatisfaction with the medication. Performance metrics like recall, precision and precision/ recall AUC are very important as they help us determine how accurate a model is in identifying especially negative reviews and whether a model is able to distinguish between the classes regardless of class imbalance, hence the model should be able to produce good scores across these metrics. A strong balance between precision and recall is essential, targeting an F1 score above 0.8 to ensure reliable and actionable predictions.
