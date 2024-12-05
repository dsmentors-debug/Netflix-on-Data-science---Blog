**How Netflix Uses Data Science for Personalization: The secrets behind recommendation engines**.

Have you ever noticed that once you finish watching one episode of your favorite Netflix show, an interesting recommendation appears that you just can’t ignore? 
That’s all because Netflix works for you by deploying AI/ML and data science to match your preferences with existing content on the platform

![NNNTT](https://github.com/user-attachments/assets/affd6cb0-4a81-4905-bf9e-90f5367b97eb)


**Why Millions of Viewers Fell in Love with Netflix?**

In simple terms, you can think of Netflix’s AI as your personal T.V match maker. It understands, your viewing preferences and uses that knowledge to help you find movies and shows that you would love.Netflix’s AI is pretty good at its job. In fact, back in 2016, Netflix CEO Reed Hastings mentioned that “Over 75% of what people watch on Netflix is discovered through our recommendation system.”
Fast forward to 2020, Netflix revealed that 80% of the content viewed on the platform comes from these personalized recommendations.

**Key Takeaways**
•	A recommendation engine is a type of data tool that uses machine learning and algorithms to recommend products, services, and information to users based on data analysis.
•	There are three main types of recommendation engines — non-personalized, content-based, and  collaborative filtering. 
•	Yish’s research shows that Netflix uses a hybrid model of content-based and collaborative filtering.

**Why Recommendation systems:**
        • Revenue
        • Customer Satisfaction
        • Personalisation
        • Discovery
        • Reports and Analytics

**So how does Netflix’s AI work?**

"Personalized recommendations on the Netflix Homepage are based on a user's viewing habits and the behavior of similar users"

•	User profile information such as age, gender, location, and selected favorite content upon sign up
•	Netflix tracks what you watch, how long you watch it, and whether you finish it.
•	If the show was paused, rewound, or fast-forwarded
•	If the viewer resumed watching after pausing
•	what titles you start watching, if you finish those titles, and how you rate those titles, such as thumbs up
•	Whether an entire TV series or movie was completed
•	Whether the viewer gave the show or movie a thumbs up
•	Scenes users have viewed repeatedly
•	The number of searches and what is searched for
•	Where a user watched the show (by postal code)
•	Browsing and scrolling behavior
•	Screen shots when the show was paused, when the user left the show, and when the user watches a scene more than once
•	Netflix then rates each show and movies based on the factors like popularity, user ratings, and how well they match your taste.

**Use Cases of AI/ML/Data Science in Netflix**

Netflix has gone beyond using data analytics to boost their business and have developed an entire research department which is integrated into their business and engineering teams. 
They’ve released open-source machine learning algorithms and Python frameworks aimed at boosting the productivity of Data Scientists and businesses.

![recomm](https://github.com/user-attachments/assets/e1fb0935-1d00-4918-b480-c8e954616471)

1.	Content-based Filtering
It uses items which are closer to each other or look like
Recommend item to user A based on ratings user A gave the last time
No need for data of other customers
It uses techniques of cosine similarity to determine the closeness of items -
        "Cosine similarity is often used in recommendation systems to suggest items or services to customers based on their preferences.
         The cosine similarity between the user and product vectors is determined, and the products with the best scores are suggested to the user."

2.	Collaborative filtering
How can we measure the similarity between users : in terms of item they purchase
How can we measure the similarity between two items: in terms of the users who purchased

3. Hybrid filtering
A hybrid recommendation system is defined as a framework that combines content-based and collaborative filtering recommendation systems to enhance performance by addressing the limitations of traditional recommendation techniques.

**Personalized Thumbnails: To attract customers**

![MMVIE](https://github.com/user-attachments/assets/b897a26d-ca45-40dc-8f62-a5867e99c659)

A personalized thumbnail, also known as a custom thumbnail, is an image that a user uploads to represent their video and attract viewers,grow their audience, and generate more attention.
A personalized thumbnail can help a user present themselves in a positive light and create a good first impression.
To make a personalized thumbnail more visually appealing, users can use bold, bright, and saturated colors, and contrasting colors

**How python used in Recommendation system**

1. Import the required libraries.
Import numpy and pandas machine learning libraries, as we will use them for data frames and evaluating correlations.
2. Get the Data
The dataset has two main files in the format of CSV:
  Ratings.csv: Contains the rating given by each user to each movie they watched
  Moviesmetadata.csv: Contains information on genre, budget, release date, revenue, and so on for all the movies in the dataset.

3.Handle missing values , lowercase and punctuation in dataset.

4. Removal of Stop words and stemming could be used for efficient data structure.
   
5.Construct a user-item matrix where rows represent users, columns represent movies, and entries represent user ratings. This matrix will serve as the foundation for collaborative filtering.

6.Divide your dataset into training and testing sets. This is essential for evaluating the performance of your recommender system accurately

7.Select a collaborative filtering algorithm for your project. User-based and item-based collaborative filtering are common choices. For this guide, we’ll use the user-based approach

8.Utilize the trained model to make predictions on the test set and evaluate its performance using metrics like Mean Squared Error (MSE) or Root Mean Squared Error (RMSE).

9.Once your model is trained and evaluated, you can generate movie recommendations for a specific user. Consider recommending movies with the highest predicted ratings that the user has not seen.

10.Depending on your goals, you can deploy the recommender system as a web application, or API, or integrate it into an existing platform. This step allows users to interact with and benefit from your personalized movie recommendations.

![pop](https://github.com/user-attachments/assets/fbcdd351-d58b-4bae-a69b-badf78f24e27)



**Conclusion**:
Every company has to keep up to date with the technology to provide the best satisfaction set of recommendations to all their users.Many things are going on in the field of recommendation engines.With a touch of AI,
you will be impressing your audience and turning them into your life long fans faster than you imagine.Stay engaged with user feedback and continuously update your model with new data to ensure its effectiveness over time.


