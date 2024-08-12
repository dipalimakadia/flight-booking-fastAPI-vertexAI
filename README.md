
# flight-booking-fastAPI-vertexAI

## Task 1: Setting up Google Gemini

Embark on your Gemini Flights Mission with Google Cloud! Create an account, verify it for free credits, set up billing, and create a dedicated project in the Google Cloud Platform.

step1: create gcloud

## Task 2: Clone Premade FastAPI Server

Set up the Gemini Flights Backend effortlessly! Clone the repository, create a virtual environment to avoid conflicts, start the FastAPI server, and test endpoints using the intuitive API interface.

git clone https://github.com/radicalxdev/mission-gemini_flights_backend.git
step 1: python -m venv env
step 2 : env\Scripts\activate
step 3: pip install -r requirements.txt
step 4:  uvicorn main:app --reload

## Task 3: Google Cloud Developer Initialization

Seamlessly integrate Google Cloud SDK for Vertex AI! Download and install the SDK, initialize it via CLI, and effortlessly set up Python for Vertex AI with proper authentication.

set up google
gcloud init
set GOOGLE_APPLICATION_CREDENTIALS=C:\Users\dmakadi\data\Radical_Projects\chat-app-gemini-streamlit-vertexai-googleapi\application_key.json

## Task 4: Function Calling with Tools

Define and load functions effortlessly for Gemini Flights! Use FunctionDeclaration to craft the get_search_flights function, encapsulate it in a Tool class, and configure the GenerativeModel with ease.

jyupter notebook

## Task 5:  Streamlit Integration

Implement a response handling system and integrate it with Streamlit for effective communication with Google Gemini. Ensure proper initialization of the chat session and handling of various response types.

## Task 6: Build the Book_Flight Tool 

Implement the book_flight function in Flight_Manager.py, define its function declaration, and update the tool class to bind the new function to Gemini for flight booking.
