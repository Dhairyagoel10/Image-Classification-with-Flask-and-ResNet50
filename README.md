## Image-Classification-with-Flask-and-ResNet50

# Project Overview
This project is an image classification web application built using Flask and a pre-trained ResNet50 model from Keras. The application allows users to upload images and receive predictions about the content of those images.

# Technologies Used
1. Python: A programming language widely used for machine learning and web development.
2. Flask: A micro web framework for Python used to create web applications.
3. Keras: A high-level neural networks API, running on top of TensorFlow.
4. ResNet50: A deep learning model used for image classification.
5. HTML: For creating the user interface.

# Features
1. Upload images for classification.
2. Displays the predicted label with confidence percentage.
3. User-friendly interface.

# Step 1: Set Up Your Environment
1. Create a Virtual Environment: Open your terminal and navigate to your project directory. Create a virtual environment to keep your dependencies organized.
[python -m venv venv]

![Screenshot 2024-09-22 223634](https://github.com/user-attachments/assets/b1283e10-ef8e-4f4c-bc5b-9f5ed1a9d1ee)

1. I used a Conda environment, but you can also use venv.
2. One important thing is to create a folder called 'images' where the images will be saved (see the photo).

3. Activate the Virtual Environment:
• On Windows  [ venv\Scripts\activate ]
• On macOS/Linux: source  [ venv/bin/activate ]

# Step 2: Run the Application
3. Run the Flask Application: In your terminal, while still in the project directory and with the virtual environment activated, run
  [ python app.py ]

# Step 3: Access the Application
Open Your Web Browser: Navigate to http://127.0.0.1:3000 to access your image classifier application.

# Step 4: Upload an Image
1. Click on the "Choose an image to upload" button.
2. Select an image from your computer.
3. Click the "Predict Image" button to see the prediction.

# Step 5: Deactivate the Environment
Deactivate the Virtual Environment: When you are done working, you can deactivate the virtual environment by running [deactivate
]
