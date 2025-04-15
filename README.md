# DiseaseDetector

https://github.com/user-attachments/assets/cec44a79-b591-41bf-a797-436e238ade2b

## Inspiration
After conducting research on diseases and illnesses that are prevalent in remote/outdoor environments, we applied our knowledge on machine learning algorithms, specifically vector classifiers and neural networks, to tackle this problem using a front-end web application. We seek to make this project accessible to individuals around the world, as an innovative method to self-diagnose diseases with high accuracy and immediate results.

## What it does
Disease Detector contains two central components: The first is a self-diagnosis test that asks a series of questions (starting with broad, generic queries and progressively asking more specific questions) in order to determine the condition. The second option is image classification, where the application prompts the user to upload an image and classifies it as a certain disease through ML techniques. Our web application receives images as input for the CNN and SVC models, which use binary cross-entropy to diagnose Lyme disease, malaria, and poison ivy. Using this application, countless individuals can receive immediate results involving medical complications.

## How we built it
We built this project using Python and an application called Streamlit to run our web-application in the front-end. Additionally, we incorporated back-end machine learning techniques that input the user's images into one of our three machine learning applications, each using layers of CNNs and SVCs to accurately diagnose between three diseases. In the question-and-answer diagnosis, we used the Kaggle dataset to determine symptoms for a wide variety of diseases. Using these symptoms, the user is prompted with questions about their symptoms until the model accurately predicts the disease or condition they are experiencing. We used Python for the self-diagnosis as well, and stored our web-application in the class app.py.

## Challenges we ran into
We encounter a few challenges when training the neural network models and incorporating it in our web-app. At first, we faced the challenge of receiving high accuracy, but eventually obtained approximately 90% accuracy while predicting diseases using image classification. We improved the accuracy by optimizing the layers and incorporating max pooling, batch normalization, and dropouts. When creating the self-diagnosis test, we faced the challenge of server hosting to the Streamlit website that we created. However, we overcame this obstacle by changing our code to efficiently run through each of the questions individually until the program was able to predict the disease.

## Accomplishments that we're proud of
Although we were previously unfamiliar with using Streamlit platform to host web applications, we were able to efficiently incorporate our machine learning model and user-friendly self-diagnosis test by researching the API and troubleshooting our code whenever there were errors with running the server host. We are also proud of being able to create accurate models, given the time restraint. We are especially accomplished of the impact that this project has on society, through incorporating disease detection for individuals in remote environments.

## What we learned
Firstly, we learned how to use the Streamlit framework to host and successfully run our web application, which is significant for individuals in remote environments where they do not have immediate access to medical assistance. We also learned how to obtain high accuracy from models using convolutional neural networks and support vector machines, which were able to predict the disease or condition through image classification. Outside of both the front-end and back-end structure we used for our website, we also learned about how significant this problem is to individuals in remote environments. Without access to immediate medical assistance, Disease Detector is a project that strives to provide expeditious diagnoses to these individuals in real-time.

## What's next for Disease Detector
Our next steps for Disease Detector are to add many more diseases in our image classification database. We plan to have a single feature that tests for all visible diseases at once, instead of separate buttons. For now, we created a web app, but our plan is to develop a functional iOS/Android application that individuals can access in remote environments (does not rely on the internet). In addition, we hope to share our solution with the local community to gauge interest and enhance our idea based on feedback.
