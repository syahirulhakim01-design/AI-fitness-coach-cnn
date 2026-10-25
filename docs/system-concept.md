# System Concept

## Overview

AI Fitness Coaching is an Android application that combines machine learning and fitness tracking techniques to provide beginner-friendly workout recommendations.

The application utilizes a Convolutional Neural Network (CNN) to classify uploaded images into predefined categories. The classification result supports the recommendation process, while fitness goals, user preferences, available equipment, and experience levels play the primary role in generating workout recommendations.

## Workflow

1. User uploads an image.
2. The image is preprocessed.
3. CNN extracts visual features from the image.
4. The classification layer predicts the image category.
5. The category is returned to the application.
6. User fitness profile data is evaluated.
7. Personalized workout recommendations are generated.
8. Users perform workouts and record activities.
9. The application stores workout history and displays progress reports.

## Technologies

### Machine Learning

- TensorFlow
- Keras
- Convolutional Neural Network (CNN)

### Mobile Development

- Android Studio
- Java
- XML

### Database

- MySQL

## Benefits

- Beginner-friendly workout guidance
- Personalized recommendations
- Workout history tracking
- Progress monitoring
- Practical application of CNN image classification technology

## Limitations

- Does not perform medical diagnosis.
- Does not provide real-time posture correction.
- Does not generate meal plans or nutrition advice.
