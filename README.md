# Football-Analysis-System-using-YOLOv8

 Project Structure
bash
Copy
Edit
.
├── dataset.csv          # FIFA 22 match dataset
├── fifa_analysis.py     # Streamlit dashboard script
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
📊 Features
Team Filtering: Select a team to view relevant match statistics.

KPIs: Displays average possession, goals, and attempts.

Interactive Table: View match stats in a scrollable table.

Trends Visualization: Line chart showing possession vs goals over time

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app

bash
Copy
Edit
streamlit run fifa_analysis.py
Open in browser
The app will launch at http://localhost:8501.

📦 Requirements
From requirements.txt:

nginx
Copy
Edit
pandas
numpy
matplotlib
streamlit
