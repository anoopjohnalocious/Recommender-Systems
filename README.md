# Recommender-Systems
Recommender Systems In-class Kaggle Competition. The proposed recommender system was able to come in the Top 30 of the competition which had over 100 students.



# Problem Description
There is rich semi-structured data on social media platforms. This dataset for this task is collected from
an online photo-sharing social media platform Flickr. People share photos with others on Flickr and
make connections (friends). The task is to recommend a list of items (photos) to each user given rich
information on this social media platform.

# Data
The user-item interaction data is the main data for this challenge. This data is further split into training, validation, and test sets.

Training data. The training dataset contains a set of interactions between users and items (photos). If a user liked a photo (e.g., click the "heart" emoji which indicates a positive engagement), then there will be a record in the dataset.
Test data. Each user is provided with a list with 100 candidate photos in the test dataset, you will need to check the candidate list and recommend the top 15 photos for each user.
Validation data. A validation dataset that you may use to tune your model. The dataset format is similar to the Test dataset, except that the ground truth of the rating is given.
Your task is to train a recommender system and generate the outputs for the test data.

In addition to the interaction data (training data), you are also provided with the following information:

Item information. Each photo is represented as a 256-dimensional embedding which is extracted from a pre-training deep learning framework.
User information. Each user is represented as a 256-dimensional feature representation, which is the average of the image feature representations she liked in the training data
Social information. If two users are friends, there will be a link between two users.
Please note that the user, item, social information are optional data for this challenge. You don't have to use it. It is your own choice to determine if the information should be used or not.

