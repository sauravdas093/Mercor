# Mercor_Project
    Clothing Item Recommender System for Mercor
##Overview
    The goal of this project is to create a machine learning model capable of receiving text describing a clothing item and returning a
    ranked list of links to similar items from different websites. This project aims to provide users with personalized recommendations
    for clothing items based on their descriptions.
##Database
    Please find the CSV files used in the project along with the project in the 'main' branch.
##Features
    Accepts text input describing a clothing item in json format
    Utilizes a machine learning model for similarity analysis using cosine similarity
    Returns a ranked list of links to similar items from various websites in json format
    Supports JSON responses for easy integration with other systems
##Installation
    To run the Clothing Item Recommender locally, follow these steps:
    Clone the repository.
    Install the required dependencies or the packages essential for the project: pip install -r requirements.txt
    Download and preprocess the necessary data or the csv file attached with this document for the machine learning model.
    Train the machine learning model.
    Run the application locally on your local IDE: python app.py
##Deployment
    To deploy the Clothing Item Recommender on Google Cloud, follow these steps:
    Create a Google Cloud account and set up a project.
    Install the Google Cloud SDK and configure it with your project credentials.
    Build a Docker image of the application: docker build -t clothing-recommender .
    Push the Docker image to the Google Container Registry: docker tag clothing-recommender gcr.io/your-project-id/clothing-recommender
    Deploy the container to Google Cloud Run: gcloud run deploy --image gcr.io/your-project-id/clothing-recommender --platform managed
    Access the deployed application using the provided URL.
##Author
    Saurav Das - sauravdas093@gmail.com
##Acknowledgments
    I would like to thank Surya Sir for giving me the opportunity to work in this project.
