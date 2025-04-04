## 🙋‍♂️ Author

**Pranav Patil**  
Master's Student | Aspiring AI Engineer  
📧 Feel free to connect or reach out for feedback and collaboration!

📧 patilpr003@email.com  
🔗 [LinkedIn](http://www.linkedin.com/in/patil04)  
💻 [GitHub](https://github.com/vrbeirer)

-----------------------------------------------------------------------

# AI Resume Screening and Ranking System

An intelligent AI-based system for automating the process of resume screening and ranking applicants based on their skills, qualifications, and job relevance. This project uses Natural Language Processing (NLP) and Machine Learning (ML) to analyze resumes and match them against job descriptions.

## 🚀 Features

- Upload and parse multiple resumes (PDF or DOCX)
- Extract relevant details: name, contact info, skills, education, and experience
- Match resumes with job description using NLP techniques
- Rank candidates based on skill and keyword matching
- User-friendly interface for uploading files and viewing results
- Resume similarity scoring
- Clean and scalable codebase

## 🛠️ Tech Stack

- **Frontend**:  Streamlit
- **Backend**: Python
- **Libraries**:
  - `spaCy` – NLP processing
  - `PyPDF2` / `docx` – Resume parsing
  - `scikit-learn` – TF-IDF and similarity matching
  - `pandas`, `numpy` – Data processing
  - `Streamlit` – (Optional) for quick UI prototyping

## 📂 Project Structure
AI-Resume-Screening-System/ ├── resumes/ # Folder containing sample resumes ├── job_description.txt # Job description file ├── app.py # Main application file ├── resume_parser.py # Resume parsing logic ├── ranker.py # Ranking logic ├── templates/ # HTML templates (if Flask used) ├── README.md # Project documentation └── requirements.txt # List of dependencies


## 🧠 How It Works

1. **Resume Parsing**: Extracts text from uploaded resumes using PyPDF2 or python-docx.
2. **Job Description Parsing**: Reads a job description and extracts required keywords.
3. **Similarity Calculation**: Uses TF-IDF vectorization and cosine similarity to compare resumes to the job description.
4. **Ranking**: Generates a ranked list of candidates with matching scores.

## 🖥️ How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Resume-Screening-System.git
cd AI-Resume-Screening-System

2. Create a virtual environment and activate it (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

3. Install dependencies:

pip install -r requirements.txt

4. Run the application:
python app.py

5. If you are using streamlit:
streamlit run app.py


