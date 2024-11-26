# AI-Project

Autonomous Vehicle Collision Detection and Emergency Notification System 

## Overview
This project focuses on developing an *Autonomous Vehicle Collision Detection and Emergency Notification System*. It uses deep learning, computer vision, and geolocation technologies to detect vehicle accidents in real-time and promptly notify emergency services. The system is designed to enhance safety in smart city environments, aiming to reduce response times and save lives.

## Folder Structure -
manage.py: The entry point for the Django project, used to execute administrative commands.

AccidentDetection/:
settings.py: Configuration settings for the Django project, including database and app settings.
urls.py: URL routing for the core project.
asgi.py: ASGI entry point for asynchronous server setups. wsgi.py: WSGI entry point for deployment with WSGI servers.
accidentdetectionapp/:
admin.py: Manages the Django admin interface for the app. apps.py: Configuration file for the application.
models.py: Defines database models for storing accident-related data and application logic.

This serves as the foundation for managing critical data within the project. views.py: Implements logic for handling HTTP requests and generating responses. 

urls.py: Application-specific URL configurations.
stream.py: A core module that enables real-time processing of live video streams to detect accidents, making it pivotal for real-time use cases.
tests.py: Includes test cases to validate the system's reliability.
migrations/: Auto-generated Django files to handle database schema changes. template/: HTML templates for rendering dynamic web pages in the application.
 
static/: Contains static assets like CSS, JavaScript, and images for the frontend interface.
db.sqlite3: The SǪLite database used for storing application data during development.
accident2.pt and best (2).pt: Pre-trained PyTorch models designed for accident detection from video and image inputs.
highway_accident.mp4: A sample video file for testing and demonstrating the system’s capabilities.
image.jpg: A sample image for testing accident detection accuracy.
test.py: A standalone script to test and validate different components of the system. 

Running the Project:
