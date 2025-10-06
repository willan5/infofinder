
A Jaclang-based search application that uses Gemini AI to provide intelligent responses to user queries.

## Features
- Interactive command-line interface
- AI-powered responses using Google Gemini
- Node/walker architecture implementation
- Handles information queries, programming questions, and general knowledge

## Prerequisites
- Python 3.8+
- Jaclang installed
- Google Gemini API key

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/willan5/infofinder.git
   

2. **Setup environment:**
   ```bash
   python -m venv myenvs/googlesearch
   source myenvs/googlesearch/bin/activate

3. **Install depedencies:**
   ```bash
   pip install -r requirements.txt

4. **Setup API Key:**
   ```bash
   # Add this to your ~/.bashrc file:
   export GEMINI_API_KEY="your_gemini_api_key_here"
   
   # Or create a .env file in project root:
   echo 'GEMINI_API_KEY="your_key_here"' > .env
