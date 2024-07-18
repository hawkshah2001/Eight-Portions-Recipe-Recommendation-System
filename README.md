# Eight-Portions-Recipe-Recommendation-System

![Screenshot 2024-07-17 at 4 04 59 PM](https://github.com/user-attachments/assets/876fae96-67e9-48ac-95da-2a9bfa3ac9bb)


# Recipe Recommendation System Project


Overview:
This project involves developing a Recipe Recommendation System that leverages natural language processing (NLP) techniques to suggest recipes based on input ingredients and steps. The system integrates data pre-processing, modeling, and visualization components to enhance the user experience and provide accurate recommendations.

Data:
The dataset consists of approximately 125,000 structured recipes scraped from various food websites. Each recipe includes the following components:

Title: The name of the recipe.

Ingredients: A detailed list of ingredients along with their measurements.

Instructions: Step-by-step preparation instructions.

Picture: An image of the resulting dish (available for roughly 70,000 recipes).
This rich dataset provides multiple elements for each recipe, making it suitable for various machine learning applications, such as recipe prediction, summarization, and generation.


# Data Pre-Processing

Stop-Words Removal: Removed common English stop-words, specific terms like "Advertisement" and "Want," and numerical values to clean the text data.
Vectorization: Utilized CountVectorizer to transform text data into a matrix of token counts.
Cosine Similarity Calculation: Computed cosine similarities between word vectors to measure the similarity between different recipes.
Modeling:

BertTopic Model: Applied the BertTopic model to generate various topics from the text data, enabling the system to understand and categorize different recipe components effectively.

String Combination: Merged the title, ingredients, and instructions of each recipe into a single string to streamline the analysis and recommendation process.


# Visualizations

Word Cloud: Created word clouds to visually represent the most frequent terms in the recipe dataset.

Bertopic Map: Generated a Bertopic map to provide a visual summary of the topics identified within the recipe data, making it easier to interpret the results.

This project demonstrates the use of advanced NLP techniques and machine learning models to build a functional and efficient Recipe Recommendation System, capable of providing personalized recipe suggestions based on user input.
