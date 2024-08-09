# Fake-News-Detection
1.Import all the needed libraries such as NumPy , Pandas , Sklearn , Matplotlib .The news dataset from the Kaggle we have taken the train csv file.
<br>
2. Identify the StopWords in English then Load the dataset to a pandas DataFrame.
<br>
3. Count the number of missing values in the dataset.Check how many rows and column the dataset has. Replace the null values with empty string . Explore each variable and identify it’s shape.
<br>
4. Merge the author name and news title . Rename it as Content. Separate the data & label.
<br>
5. Remove the commoner morphological and inflexional endings from words in English using Porter Stemmer. The resultant stem is a shorter word with the same root meaning.
<br>
6.Identify the shape of the label and then convert the textual data to numerical data. Using  Tf-idfVectorizer and then fit and transform that numeric  converted data .
<br>
7. Train , Test and split data with random state . In other word, ensure that the same randomization is used each time you run the code, resulting in the same splits of the data.
<br>
8.Run the below mentioned model and find accuracy, classification report and confusion metrics using Logistic regression and Decision Tree.
<br>
9.Find the Variable that impacts the most and make WordCloud of Real and Fake Words in that particular dataset.
<br>
10.Make graph of Top 20 frequent words that are in the dataset
