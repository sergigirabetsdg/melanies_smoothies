🥤 Melanie's Smoothies

Melanie's Smoothies is an interactive application built with Streamlit that allows users to customize and submit smoothie orders with their favorite fruits. The data is stored in a Snowflake table, enabling advanced integrations in cloud and enterprise environments.

🚀 What does this app do?

Lets you enter the name on your smoothie.

Allows you to choose up to 5 ingredients/fruits.

Inserts your order into a Snowflake database.

Displays confirmation messages when the order is submitted successfully.

🧱 Requirements

Make sure you have Python 3.8+ installed.

Install the dependencies from the requirements.txt file:

pip install -r requirements.txt

🧪 Run locally

To launch the app in your browser:

streamlit run streamlit.py

This will open the app in your browser at http://localhost:8501.

🔐 Snowflake Connection

Make sure you have your .streamlit/secrets.toml file or your environment set up with the following connections.snowflake configuration:

[connections.snowflake]
account = "..."
user = "..."
password = "..."
role = "..."
warehouse = "..."
database = "..."
schema = "..."
client_session_keep_alive = true

📂 Project Structure

melanies_smoothies/
├── streamlit.py              # Main app
├── requirements.txt          # Dependencies
└── README.md                 # (this file)

👩‍🍳 Credits

This project is part of an interactive workshop on Streamlit + Snowflake.

