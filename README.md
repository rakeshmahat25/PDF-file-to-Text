# Create Virtual ENV
python -m venv venv

# Activate venv

.\venv\Scripts\activate 

# Download required Library
pip install -r requirements.txt

# Run the project 
uvicorn main:app --reload
