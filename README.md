
# Toxic Comment Classification App

This is a web application built with Streamlit to analyze the toxicity levels in user-submitted comments. The app uses a pre-trained XGBoost model to classify comments into six categories of toxicity.

## Features

- **Text Input**: Users can input a comment to analyze.
- **Toxicity Categories**:
  - Toxic
  - Severe Toxic
  - Obscene
  - Threat
  - Insult
  - Identity Hate
- **Real-Time Analysis**: Instant predictions based on user input.

---

## Installation

Follow these steps to set up and run the app locally:

### Prerequisites
- Python 3.7 or higher
- `pip` (Python package manager)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/toxic-comment-classifier.git
   cd toxic-comment-classifier
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run streamlit_app.py
   ```

4. Open the app in your browser at `http://localhost:8501`.

---

## File Structure

```
.
├── streamlit_app.py           # Main application script
├── toxic_comment_model_xgb.pkl # Pre-trained XGBoost model
├── requirements.txt           # Dependencies
├── README.md                  # Documentation
```

---

## Deployment

### Deploy on Streamlit Cloud
1. Push the project to a GitHub repository.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud).
3. Select your GitHub repository and deploy the app.

### Other Platforms
You can deploy this app on platforms like **Heroku** or **AWS** by following their respective deployment guides.

---

## Model Information

The application uses a pre-trained XGBoost model saved as `toxic_comment_model_xgb.pkl`. The model was trained on the [Kaggle Toxic Comment Dataset](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) and can predict the following toxicity levels:
- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

---

## Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

For questions or suggestions:
- **Name**: Your Name
- **Email**: your_email@example.com
- **GitHub**: [your_username](https://github.com/your_username)
