# Personality Classifier (Introvert vs Extrovert)

This is a simple machine learning project that classifies a person as an **Introvert** or **Extrovert** based on their responses to a few behavioral questions.

## Features Used

- Time_spent_Alone
- Stage_fear (yes/no)
- Social_event_attendance (scale 1–10)
- Going_outside (scale 1–10)
- Drained_after_socializing (yes/no)
- Friends_circle_size (1–15)
- Post_frequency (scale 1–10)

## Model Used

- **Decision Tree Classifier** (scikit-learn)
- Trained with above features and saved using `pickle`.

## How to Use

### 1. Train the Model (Optional if already trained)
Run the Python script to:
- Load or create the dataset
- Encode categorical values
- Train a Decision Tree model
- Save the model (`personality_model.pkl`) and label encoder (`label_encoder.pkl`)