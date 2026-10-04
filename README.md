# MacroSnap

MacroSnap is a Streamlit chat app where a student enters their name and WhatsApp number once, chats with an AI nutrition buddy (typing a question or attaching a meal photo), and receives calorie/macro estimates. Sending a full conversation summary to WhatsApp is handled via Twilio.

## How to Run Locally
1. Clone repository
2. Create and activate a virtual environment (`python -m venv venv`)
3. Install dependencies (`pip install -r requirements.txt`)
4. Create `.streamlit/secrets.toml` with your credentials
5. Run `streamlit run app.py`