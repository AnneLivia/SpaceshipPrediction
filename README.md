# Spaceship Titanic

### In this project, it has been used different Machine Learning models to Predict which passengers are transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly. To make these predictions, there's a set of personal records recovered from the ship's damaged computer system.

Dataset obtained from <a href="https://www.kaggle.com/c/spaceship-titanic/overview">this link</a> on Kaggle.

Models implemented by <a href="https://github.com/AnneLivia">Anne Livia</a>.

### Description
 
Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

<div align="center">
<img src="https://storage.googleapis.com/kaggle-media/competitions/Spaceship%20Titanic/joel-filipe-QwoNAhbmLLo-unsplash.jpg" width=50%>
</div>

To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.

Help save them and change history!

Acknowledgments
Photos by <a href="https://unsplash.com/@joelfilip?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Joel Filipe</a>, <a href="https://unsplash.com/@uncle_rickie?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Richard Gatley</a> and <a href="https://unsplash.com/@actionvance?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">ActionVance</a> on Unsplash.

### Dataset Information

- ***train.csv*** - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.
    - **PassengerId** - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
    - **HomePlanet** - The planet the passenger departed from, typically their planet of permanent residence.
    - **CryoSleep** - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
    - **Cabin** - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
    - **Destination** - The planet the passenger will be debarking to.
    - **Age** - The age of the passenger.
    - **VIP** - Whether the passenger has paid for special VIP service during the voyage.
    - **RoomService**, **FoodCourt**, **ShoppingMall**, **Spa**, **VRDeck** - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
    - **Name** - The first and last names of the passenger.
    - **Transported** - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
- ***test.csv*** - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of Transported for the passengers in this set.

# Software Information

  - Python
  - Pandas
  - Scikit-learn
  - Seaborn
  - XGBoost

# Trained Models 

  - Decision Tree Model
  - Random Forest Model
  - Extra Tree Model
  - XGBoost model
  - AdaBoost model
  - K-nearest neighbors (KNN)
  - Support vector machine (SVM)
  - Multi-layer Perceptron Classifier 

# Kaggle Competition
  - The best model (Random Forest) was used to predict the test dataset and the result from this prediction was submitted to Kaggle.
  - The final score considering Accuracy metric was: 0.79144.
  - Later improvements will still be done to achieve a higher score in the competition.
