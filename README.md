Smart Money Crypto Dashboard
=============================

This dashboard helps users track smart money movements in the cryptocurrency space. It provides visual insights into whale activity, token inflows/outflows, and alerts for specific tokens like XRP and SUI.

---

📦 Features

- Top wallet movements
- Whale buy/sell activity
- Token inflows/outflows
- XRP & SUI smart money alerts
- Summary of smart money trends

---

📦 Requirements

- Python 3.7+
- dash
- dash-bootstrap-components
- gunicorn (for deployment)

Install dependencies using:

    pip install -r requirements.txt

---

⚙️ Installation

1. Clone the repository:

    git clone https://github.com/yourusername/smart-money-dashboard.git
    cd smart-money-dashboard

2. Install dependencies:

    pip install -r requirements.txt

3. Run the app locally:

    python app.py

---

🚀 Deployment on Render

1. Create a GitHub repository and push your code.
2. Create a `requirements.txt` and `Procfile`:

    requirements.txt:
        dash
        dash-bootstrap-components
        gunicorn

    Procfile:
        web: gunicorn app:server

3. Go to https://render.com and create a new Web Service.
4. Connect your GitHub repo and set the start command to:

        gunicorn app:server

5. Deploy and get your public URL.

6. Embed in WordPress using:

    <iframe src="https://your-dash-app.onrender.com" width="100%" height="800px" frameborder="0"></iframe>

---

👤 Attribution

Created by Kevin Brownfield.  
For inquiries or commercial licensing, please use the contact form at:  
https://kevinbrownfield.com

