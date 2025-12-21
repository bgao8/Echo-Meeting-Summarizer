## Echo

Echo is an AI-powered meeting transcription and summarization tool built in Python.  
Its goal is to help users retain and extract information from long-form conversations.

The project was motivated by my experience in hours-long Zoom meetings and online classes where many topics are discussed quickly. 
As someone who likes to take thorough notes, I often found it difficult to keep up in real time. 
Echo was built as a personal solution to aid my ability to stay focused and accurately capture important details.

This project also represents my first foray into frontend-style interaction. 
To keep the focus on core functionality, the interface is implemented in a Jupyter Notebook rather than a full React/JavaScript frontend, which I began learning later.

## Key Features
- **Live audio recording** from a selected microphone  
- **Real-time speech transcription**
- **AI-powered summarization**, including:
  - Concise meeting overview  
  - Key discussion points  
  - Potential action items or decisions
- **Interactive Q&A**: Ask questions about the ongoing meeting while recording continues

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/echo.git
   cd echo
   
2. (Recommended) Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows

3. Install dependencies:

pip install -r requirements.txt

## Usage Guide
**Start Recording**
1. Select your microphone from the dropdown menu.
2. Click Start Recording.
3. Wait 5–10 seconds, then begin speaking or play audio through the selected microphone.

**Ask a Question**
1. Type a question into the text box.
2. Press ENTER to submit.
3. Recording continues uninterrupted while your question is processed.

**Summarize**
Generates a structured summary containing:
- A brief overview
- Key points discussed
- Possible decisions or next steps

**Stop Recording**:
Press "Stop Recording" to end the session.

# Tech Stack
- Python
- Jupyter Notebook (interactive UI)
- Speech-to-text pipeline
- AI-based text summarization
