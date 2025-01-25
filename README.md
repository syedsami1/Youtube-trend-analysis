
# YouTube Trend Analysis with CrewAI and BrightData

Dive into YouTube trends with the powerful combo of CrewAI and BrightData! This project lets you analyze the latest video trends and generate insightful summaries.

## Setup and Installations

**BrightData API Key:**
- Head over to [Bright Data](https://brdta.com/dailydoseofds) and create an account.
- Grab your API key from the API Key page.
- Save your key in a `.env` file like this:
  ```env
  BRIGHT_DATA_API_KEY=your_api_key
  ```

**Get Ollama Running on Windows:**
1. [Download the Ollama installer](https://ollama.com/download/OllamaSetup.exe) 
2. Run the installer and follow the installation steps.
3. Open the integrated terminal in VS Code (press `Ctrl + ` `).
4. Pull the llama 3.2 model with:
   ```sh
   ollama pull llama3.2
   ```

**Installing Dependencies:**
Ensure Python 3.11+ is installed. Then run:
```sh
pip install streamlit ollama crewai crewai-tools
```

## Running the Project

Fire up the project with:
```sh
streamlit run app.py
```
