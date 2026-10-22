User Behavior Clustering (KMeans)

For the unsupervised project, I used KMeans clustering model

Validation:
Silhouette Score = 0.57

This is a strong score.

Important note:

Scores close to 0.7 or higher often indicate data is too simple or artificially clean
A score around 0.5–0.6 suggests meaningful, realistic clustering
👥 Cluster Insights

From the model, I identified 3 types of users:

Cluster 1 → Active Users
High time spent
High feature usage
Frequently interact with notifications

These are your power users

Cluster 0 → Medium Users
Moderate usage
Not very frequent
Average engagement

These are users you can push to become active

Cluster 2 → Low Users
Very low activity
Minimal feature usage
Low engagement

These users are at risk of churning or leaving the platform
I used the Elbow Method to find the mathematical 'bend' (Inertia) and cross-referenced it with the Silhouette Score (34.6%) to ensure the clusters were distinct enough for business use.