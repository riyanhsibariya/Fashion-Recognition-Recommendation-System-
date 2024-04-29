# Fashion-Recognition-Recommendation-System-
AI-powered clothing recognition  system

AI-powered clothing 
recognition system designed to deliver personalized recommendations to consumers effortlessly. 
The system is capable of identifying various types of garments within images and subsequently 
offering accurate suggestions for related fashion items. By leveraging open-source computer 
vision libraries such as TensorFlow and OpenCV, this solution streamlines both development 
and integration processes with other applications, ensuring accessibility and versatility.
Workflow 
1. Feature Extraction (app.py): Utilizes the ResNet50 model to extract features from a 
dataset of fashion images. Saves the feature vectors and filenames to 'embeddings.pkl' 
and 'filenames.pkl' files. 
2. Testing (test.py): Loads the saved feature vectors and filenames. Extracts features from a 
sample image and finds the most similar fashion items. Displays the top 5 recommended 
items. 
3. User Interface (main.py): Utilizes the Streamlit framework to create a user-friendly 
interface. Allows users to upload an image and obtain fashion recommendations based on 
similarity. 
4. Feature Extraction and Recommendation (main.py): Extracts features from the user
uploaded image. Utilizes the pre-trained model and Nearest Neighbors algorithm to find 
similar items. Displays the recommendations to the user. 
5. Error Handling (main.py): Ensures the system handles potential errors during file uploads 
gracefully. 
