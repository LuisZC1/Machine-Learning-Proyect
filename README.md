# Analysis of Hate Speech in Tweets Towards Indigenous Populations

# Dataset Origin:
The dataset was provided by Yachay Tech University. It was divided into four sections, with four students manually classifying each tweet, determining whether it was hateful (Hate, labeled as 1) or not (labeled as 0).

# Tools and Analysis:
From the dataset analysis, we identified specific words and phrases commonly associated with hate speech against indigenous groups. Using this insight, a Python script named Testeo de verificación.py was developed. This tool scans the dataset's tweets, cross-referencing their content with a predefined set of hate-associated terms. If a match is detected, the tweet is automatically labeled as Hate (1).

This method led us to introduce a "double verification" column in the dataset. This ensures a blend of manual and automated classifications, aiming for more accurate hate speech detection.

# Google Colab:
For a comprehensive analysis, we carried out the dataset's review and breakdown on Google Colab, where you can observe:

The number of instances per class.
The evolution of each instance over time.
The "cloudwords" from the entire dataset and from segments exclusively containing hate speech.
The execution of three experiments using double verification, a k-Nearest Neighbors (knn) model, and a combination of both to contrast the outcomes.
Access the detailed analysis on Google Colab here.
https://colab.research.google.com/drive/1OfVlTLfUNYyFKPAHULP0l0hdnjUqtb5n?usp=sharing
