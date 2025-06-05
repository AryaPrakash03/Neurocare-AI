NeuroCare AI: Brain Tumor Detection and Classification

Overview

NeuroCare AI is a deep learning-powered web-based tool designed to detect and classify brain tumors from MRI scans. Built with VGG16 and an intuitive Django-based frontend, this system aids early diagnosis, supporting healthcare professionals in medical decision-making.

Features

MRI Image Upload: Users can upload MRI images directly to the platform.

AI Detection Engine: Integrates a pre-trained VGG16 model to detect brain tumors.

Classification Output: Differentiates between tumor and non-tumor cases.

User Authentication: Secure login/registration system to manage usage.

Admin Panel: For managing and tracking user inputs and outputs.

Responsive UI: Clean and easy-to-use interface with sections like Home, About, Detection, Contact Us.

Modules

Home: Entry point with system summary.

About: Project description, motivation, and how it works.

Detection: Upload and predict results with real-time feedback.

Login/Register: Secure authentication and user session management.

Contact Us: Basic contact interface.

Tech Stack

Frontend: HTML, CSS, Bootstrap

Backend: Django (Python)

Model: VGG16 using TensorFlow & Keras

Database: SQLite (via Django ORM)

Environment: Google Colab (for model), VS Code/PyCharm (for local dev)

Model Information

Model Used: VGG16 (pre-trained)

Training Dataset: Publicly available brain MRI datasets

Input Shape: 224x224

Fine-tuning: Top layers retrained to specialize in tumor classification

Accuracy: 95%+ on validation set

System Requirements

Software:

Python 3.x

Django 4.x

TensorFlow, Keras

SQLite (default with Django)

Google Colab / Jupyter (for training model)

Hardware:

4GB+ RAM

GPU (optional but recommended for training)

Internet connection (for Colab use)

Future Enhancements

Add multi-class classification for tumor types.

Integration with hospital databases.

Real-time chat with doctors.

PDF reports for detection.

Use of better architectures like ResNet or Vision Transformers.

Team Roles

Naresh Rawat – Backend & Model Integration
Develop and integrate the VGG16 model for brain tumor classification using MRI images.

Handle image preprocessing and prediction pipeline in Python.

Configure and manage Django views, models, and URLs.

Ensure smooth backend logic integration with the frontend.

Arya Prakash Shrivastav – Testing & Debugging
Conduct Alpha and Beta testing for performance and reliability.

Identify bugs and test edge cases for model predictions.

Validate Django form behaviors (login, registration, etc.).

Prepare test reports and feedback for iterative improvements.

Janhvi – Frontend Development & UI Design
Design clean and user-friendly UI using HTML, CSS, and Django templating.

Build responsive pages for Home, About, Detection, Contact, Login/Register, and results display.

Implement styling and page layout consistency.

Assist in integrating frontend with Django backend.

Madhurita – Database Management & Reporting the File
Set up and manage Django’s default database

Configure Django admin panel to handle user records.

Ensure secure storage of user credentials and access rights.

Report making of the project

License

This project is licensed under the MIT License. Copyrights are subjected to respected team members.
