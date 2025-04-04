# HackByte_3.0
# 🌱 PlantCare- Interactive Plant Healthcare App

## Project Overview
PlantCare is an interactive application designed to help users care for their plants through a personalized, engaging interface. The app features expressive plant avatars that communicate care needs, an intuitive dashboard for monitoring multiple plants, and a chat-based interaction system.

## ✅ Current Progress (Checkpoint 1)

### Authentication System
- **MERN Stack Authentication** implemented with JWT tokens
- **CloudFlare Turnstile Captcha** integration for enhanced security
- Secure user registration and login flows with email verification

### Frontend Development
- **Complete Design System**
  - Custom color palette with plant-themed colors
  - Typography system with friendly, rounded fonts
  - Reusable component styles and animation guidelines

- **Responsive Layout & Navigation**
  - Desktop sidebar navigation
  - Mobile-optimized bottom navigation bar
  - Smooth page transitions with Framer Motion

- **Dashboard Implementation**
  - Responsive grid layout for plant cards
  - Status indicators for plant health/needs
  - Filter and sort capabilities

- **Plant Avatar System**
  - SVG-based plant avatars with dynamic expressions
  - Different growth stages (seedling, young, mature)
  - Support for multiple plant types (rose, fern, succulent)
  - Animations for different plant states

### Tech Stack
- **Frontend**: React.js, Tailwind CSS, Framer Motion
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT, CloudFlare Turnstile
- **State Management**: React Context API

## 🚀 Next Steps

### Frontend
- Plant detail/interaction page
- Chat interface for plant-human dialogue
- Add new plant flow
- Notification components
- Settings & profile page

### Backend (Planned)
- Plant data models and API endpoints
- Real-time notification system
- User preferences storage
- Care history tracking

### ML Components (Planned)
- Plant identification from images
- Personalized care recommendations
- Health analysis from plant photos

### AI Component: Plant Disease Diagnosis

🌿 AI-powered Plant Health Monitoring

PlantCare integrates an AI-driven model to diagnose plant diseases and provide care recommendations. Users can scan their plants and receive instant feedback on possible diseases and treatment suggestions.

📊 Ensure Healthy Plants
Diagnose plant diseases in home gardens, balconies, or indoor spaces using AI-driven analysis.
Provide real-time recommendations to help users maintain plant health.

📈 Leverage Data for Improvement
Collect plant health data from users to improve disease identification accuracy.
Optimize personalized care tips based on user feedback and historical plant health trends.

📂 Dataset
Currently using a shorter dataset for model training.
Training Images: 70,029
Testing Images: 17,572

Source: Plant Disease Classification - Merged Dataset

🛠 Preprocessing Steps

Image Filtering: Remove noise and enhance image quality.
Segmentation: Focus on affected plant areas for better model input.
Labeling: Organize data into specific categories (e.g., leaf spots, blight, healthy).

🔄 Data Augmentation

Rotate, crop, and adjust brightness of images to simulate real-world scenarios.

🔧 Frameworks and Tools

Machine Learning: TensorFlow & Scikit-learn
Data Manipulation: NumPy, SciPy & Pandas

🧠 Algorithm

Model: Convolutional Neural Networks (CNNs) using Keras or TensorFlow

🔍 Workflow

Feature Extraction: Identify key patterns like discoloration, lesions, or fungal growth.
Model Training: Train a CNN-based model for plant disease classification.

Prediction & Recommendation: Provide users with disease analysis and care suggestions.

📊 Performance Metrics

Accuracy: 0.98
Macro Average: 0.98 (Precision: 0.98, Recall: 0.98, F1-score: 0.98)
Weighted Average: 0.98 (Precision: 0.98, Recall: 0.98, F1-score: 0.98)

🚀 Future Enhancements

Automated Watering Reminders based on AI-predicted plant health trends
Integration with Smart Plant Sensors for real-time environmental monitoring
Community Feature to connect plant enthusiasts and share care tips

## 🛠️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Divanshu0212/HackByte_3.0

# Install dependencies
npm install

# Start development server
npm run dev
```


