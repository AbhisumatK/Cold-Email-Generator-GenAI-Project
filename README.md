# Cold-Email-Generator
Cold email generator for services company using Groq, Langchain and Streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions.
** Imagine a scenario:- **
- Intuit needs a Sr. Machine Learning Engineer and is spending time and resources in the hiring process, on boarding, training, etc.
- Deloitte is Software Development company can provide a dedicated software development engineer to Intuit. So, the business development executive (Abhisumat) from Deloitte is going to reach out to Intuit via a cold email.
# Set-Up 
To get started we first need to get an API_KEY from here: 
[https://console.groq.com/keys].
Inside `app/.env` update the value of GROQ_API_KEY with the API_KEY you created.
** To get started, first install the dependencies using: ** 
```
pip install -r requirements.txt
```
 
** Run the streamlit app: **
```
streamlit run app/main.py
``` 
