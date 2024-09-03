---
title: "Movie Recommendation System"
description: "End to end Movie recommendation system using techniques like Item-based collaborative filtering and User-based collaborative filtering."
weight: 5

---

An End-to-end fully functional Movie recommendation system for OTT streaming platforms, using techniques of Collaborative filtering. {{<badge>}}New !!!{{</badge>}}

<div>
{{< video "movie_recommendation_system.mp4" "movie_recommendation" >}}
</div>

### Pega Implementation:

<div>
{{< video "Pega_implementation.mp4" "movie_recommendation_pega" >}}
</div>

<div align="justify">In today's digital age, personalized content recommendations play a crucial role in enhancing user experience on Over-the-Top (OTT) and Digital E-commerce platforms. Leveraging advanced data science techniques and cloud technologies, I recently embarked on a project to build a recommendation system for an OTT streaming platform, and I'm excited to share my journey below!.</div>
<br>
<div align='justify'>The development process began with data collection and preprocessing, followed by implementing Item-based and User-based collaborative filtering algorithms using Python and libraries like pandas and scikit-learn. Item-based collaborative filtering also known as Item-Item similarity is a technique where the items are suggested that are similar to the items that the users had interacted with in the past. The similarity scores between the items were calculated by using metrics like Pearson-correlation and Cosine-similarity.</div>
<br>
<div align="justify">The Other technique that was used to generate recommendations was User-based collaborative filtering also known as User-User similarity. Items recommended using this technique are those which are preferred by the users that are similar to the target user. On the sparse User-Item Interaction matrix, techniques like Matrix Factorization was applied to derive 2 lower dimensional matrices representing users and items with unknown features. These unknown features were later leveraged to provide the recommendations to the target user.</div>
<br>
<div align="justify">An interactive Streamlit application was built on top of these algorithms, which was later dockerized in a container and hosted in Amazon ECS, enabling the application to be easily accessed by users. It is also hosted in Streamlit Community Cloud and can be accessed using the link below!.</div>

Link: [Movie Recommendation System](https://recommendationsystem-ak.streamlit.app/)

{{< alert "github" >}}
You can find the source code here [Github](https://github.com/Akash080799/Recommendation_System).
{{< /alert >}}
<br>
{{< alert "linkedin">}}
Check out the LinkedIn post [here!!](https://www.linkedin.com/posts/aksivakumar_movierecommendation-datascience-streamlit-activity-7190048748775903234-o_Cq?utm_source=share&utm_medium=member_desktop)
{{< /alert >}}
