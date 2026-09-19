# Activity 4 – High-Level Architecture

## Architecture Overview

The FitFlow application uses a React Native mobile frontend connected to a Node.js and Express backend. Firebase provides data storage, real-time functionality, authentication and notifications.

TensorFlow Lite is used for on-device personalization and Google ML Kit is used for computer vision and nutrition recognition.

## Main Components

1. React Native mobile application
2. Node.js + Express backend
3. Firebase services
4. TensorFlow Lite
5. Google ML Kit

## Personalized Workout Data Flow

1. The user interacts with the React Native application.
2. User fitness information is processed.
3. TensorFlow Lite provides on-device personalization.
4. The application generates personalized workout recommendations.
5. Relevant information is stored through the backend and Firebase services.

## Social Sharing Data Flow

1. The user creates or interacts with community content.
2. React Native sends the request to the backend.
3. The backend performs authentication and authorization checks.
4. Firebase stores the relevant community information.
5. Real-time updates can be delivered to other users.

## Nutrition Tracking Data Flow

1. The user captures an image using the mobile application.
2. Google ML Kit analyses the image.
3. Food information is identified.
4. The user can confirm or modify the result.
5. The information is stored for nutrition tracking.

## Security

- Authentication
- Authorization
- HTTPS/TLS
- Input validation
- Secure handling of credentials
- Access control
- Minimal collection of user information

## Scalability

Firebase managed services and scalable backend deployment can support increasing numbers of users. On-device AI processing can also reduce unnecessary server-side processing.

## Performance

React Native supports cross-platform mobile development, while TensorFlow Lite allows selected AI processing to occur directly on the device.
