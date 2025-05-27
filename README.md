# NoteMap AI

NoteMap AI is a web application that converts your class notes into interactive mind maps using AI. Upload your notes in PDF, DOCX, or TXT format and get a beautifully rendered mind map to help you study and understand the content better.

## Features

- 📄 Upload notes in PDF, DOCX, or TXT format
- 🧠 AI-powered content analysis
- 🌳 Interactive mind map visualization
- 📝 Click nodes to view relevant note excerpts

## Prerequisites

- Python 3.8+
- Node.js 16+
- Google Gemini API key

## Setup

### Backend

1. Navigate to the backend directory:
```bash
cd backend
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the backend directory:
```
GOOGLE_API_KEY=your_gemini_api_key_here
```

5. Start the backend server:
```bash
uvicorn main:app --reload
```

### Frontend

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will be available at `http://localhost:3000`.

## Usage

1. Open your browser and go to `http://localhost:3000`
2. Click the upload area or drag and drop your notes file (PDF, DOCX, or TXT)
3. Wait for the AI to process your notes
4. Explore your interactive mind map!

## Technologies Used

- Frontend:
  - React
  - TypeScript
  - Mantine UI
  - React Flow
  - Axios

- Backend:
  - FastAPI
  - PyMuPDF
  - python-docx
  - Google Gemini AI

## License

MIT 