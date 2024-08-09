## Quickstart  
To run the app, follow these steps in order:  
  
1. Create a `.env` file from the existing template for storing OpenAI and Tavily api keys.  
   ```
   cp .env.example .env
   ```
   Now, set the `OPENAI_API_KEY` and `TAVILY_API_KEY` fields in the newly created env file.
   
3. Create a python virtual environment (ensure python version is `>3.10`).  
   ```
   python3 -m venv .venv
   source .venv/bin/activate
   pip3 install -r requirements.txt
   ```
   
4. Now, it is time to run the app:  
   ```
   python -m uvicorn main:app --reload
   ```
  
The app should have started on `localhost:8000`. 
