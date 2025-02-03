# Bill2Tip - AI-Powered Tip Prediction App 💰

## Overview
Bill2Tip is a machine learning-powered web application that predicts the tip amount based on the total bill, dining time, and number of people. This project is built using **Streamlit** for the frontend and a **machine learning model** trained with historical tipping data.

## Features 🚀
- Predicts tip amounts based on **total bill**, **time of dining (Lunch/Dinner)**, and **party size**.
- User-friendly web interface built with **Streamlit**.
- Trained **machine learning model** using real-world tipping data.
- Instant predictions with a simple button click.

## Demo 🎥
Run the app locally to test the tip prediction in real time.

## Installation & Setup 🛠️
### Prerequisites:
- Python 3.x
- Streamlit
- Pandas
- Pickle (for loading the trained model)

### Steps to Run the Project:
1. **Clone the repository**
   ```sh
   git clone https://github.com/ad1lhasan/Bill2Tip.git
   cd Bill2Tip
   ```
2. **Create a virtual environment (optional but recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the Streamlit app**
   ```sh
   streamlit run stream_test.py
   ```
5. Open **http://localhost:8501/** in your browser.

## File Structure 📂
```
Bill2Tip/
│-- tip_prediction_model.pkl   # Trained ML model
│-- stream_test.py             # Streamlit app script
│-- requirements.txt           # Required Python packages
│-- README.md                  # Project documentation
```

## Usage 🏗️
1. Enter the **Total Bill Amount ($)**.
2. Select the **Dining Time (Lunch/Dinner)**.
3. Enter the **Number of People in the party**.
4. Click **Predict Tip** to get an estimated tip amount.

## Technologies Used 🖥️
- **Python** 🐍
- **Streamlit** 🎨 (for UI)
- **Scikit-learn** 🤖 (for ML Model)
- **Pandas** 🗂 (for data handling)

## Contributing 🤝
Pull requests are welcome! If you have suggestions for improving the model or UI, feel free to open an issue or fork the repository.

## License 📜
This project is licensed under the **MIT License**.

---
Happy Tipping! 💵🎉

