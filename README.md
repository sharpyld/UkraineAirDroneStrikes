# UkraineAirDroneStrikes
The Russo-Ukrainian War: An Analysis of the Russian Air/Drone Strikes on Ukraine

# Introduction
Russian air and drone strikes are a defining
feature of the Russo-Ukrainian war, causing
widespread destruction and civilian casualties.
Understanding the scale and impact of these
attacks is crucial for policymakers, humanitarian
organizations, and conflict analysts. Despite
existing datasets, integrated analysis linking
Unmanned Aerial Vehicle (UAV) patterns with
broader conflict dynamics remains limited. This
project’s goal is to understand geographic and
fatality patterns based on past airstrike data.

# Data Sources (2022-2026)
1. Armed Conflict Location & Event Data
(ACLED)
• Conflict events, actors, locations, and
fatalities across Ukraine
2. UAV attack data & model specifications
(Kaggle Open Data)
• Ukrainian developer tracking media outlets
and posting data to Kaggle
• Detailed records of launched/destroyed
missiles & UAVs, including model info and
target

# Modeling
After multiple iterations and evaluation,
“Random Forest” (RF) model selected to predict
presence of casualties on given airstrike for
increased interpretability. Top features:
• Day of year
• Longitude/Latitude of target
• Population of target city

# RF Model Evaluation
Using 80%-20% training and test split, model
was cross-validated using standard metrics.
Results below, showing successful and
accurate prediction of fatality presence for
given strike.
Accuracy = 0.90 Recall = 0.90
F1-Score = 0.90 Precision = 0.89

# Key Findings & Conclusion
Our investigation into the Ukraine conflict,
with a special focus on UAV strikes, has
uncovered significant insights. The war
involves a substantial number of events,
with over 6,000 airstrikes directly leading to
over 10,000 deaths. Geographically, certain
areas like Donetsk and Luhansk on the
eastern region, closer to the battlefront of
the war, consistently endure a
disproportionately high number of airstrikes,
correlating with greater casualties. Our
predictive analysis further confirms
that where and when these events occur
are crucial factors in determining their
severity and the number of casualties. This
predictive capability offers a powerful tool
for understanding and potentially mitigating
the human cost of these attacks.
Understanding the intricacies of the war in
Ukraine has many societal and ethical
implications. Our hope with this research is
to meaningfully contribute to the ongoing
analysis of the war effects in Ukraine.

# Societal Implications
Humanitarian Aid
• Identifying high-risk areas and understanding casualty patterns
can inform targeted humanitarian efforts.
Policy & Defense
• Insights into attack types and locations can aid in developing
more effective defense strategies and resource allocation.
Conflict Monitoring
• Predictive models can contribute to early warning systems for
escalating violence and influence military and policy responses.
