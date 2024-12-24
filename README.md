# Live-Meeting-Summary-and-Translation-Tool




# **Live Meeting Summary and Translation Tool** 📝  

## **Overview**  
The **Live Meeting Summary and Translation Tool** is a Python-based program designed to enhance virtual meetings by providing real-time summaries, keyword extraction, and translation. It integrates seamlessly with platforms like Google Meet, helping users capture essential information and overcome language barriers during meetings.  

---

## **Features**  
- **Speech-to-Text Conversion**: Converts meeting audio into text in real time using Google Speech-to-Text API.  
- **Summarization**: Generates concise summaries of discussions using Hugging Face models.  
- **Keyword Extraction**: Highlights key points and keywords using NLTK/spaCy.  
- **Live Translation**: Translates the extracted summaries into multiple languages via Google Translate API.  

---

## **Technologies Used**  
- **Programming Language**: Python  
- **APIs and Libraries**:  
  - [Google Cloud Speech-to-Text API](https://cloud.google.com/speech-to-text)  
  - [Hugging Face Transformers](https://huggingface.co/transformers/)  
  - [spaCy](https://spacy.io/)  
  - [NLTK](https://www.nltk.org/)  
  - [Google Translate API](https://pypi.org/project/googletrans/)  
  - [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/)  

---

## **Getting Started**  

### **Prerequisites**  
1. Python 3.8+  
2. Google Cloud account with Speech-to-Text API enabled.  
3. Install dependencies:  
   ```bash
   pip install google-cloud-speech googletrans==4.0.0-rc1 transformers nltk spacy pyaudio
   ```  
4. Download and set up the [Google Cloud SDK](https://cloud.google.com/sdk/docs/install) for authentication.  

---

### **Installation**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/Live-Meeting-Summary-Tool.git
   cd Live-Meeting-Summary-Tool
   ```  
2. Install required libraries (if not already installed):  
   ```bash
   pip install -r requirements.txt
   ```  
3. Set up Google Cloud credentials:  
   ```bash
   export GOOGLE_APPLICATION_CREDENTIALS="path/to/your/credentials.json"
   ```  

---

## **Usage**  

### **Step 1: Run the Tool**  
Run the main script:  
```bash
python main.py
```  

### **Step 2: Features in Action**  
- Start recording live audio.  
- View real-time transcription, summary, keywords, and translation output in the console.  

---

## **Project Structure**  
```
Live-Meeting-Summary-Tool/  
├── main.py              # Main script to run the tool  
├── audio_capture.py     # Module for recording audio  
├── speech_to_text.py    # Speech-to-text functionality  
├── summarization.py     # Summarization logic  
├── keyword_extraction.py # Keyword extraction logic  
├── translation.py       # Translation module  
├── requirements.txt     # Dependencies list  
└── README.md            # Project documentation  
```  

---

## **Future Enhancements**  
1. **Browser Extension**: Integrate directly with Google Meet via a Chrome extension.  
2. **Multi-Speaker Identification**: Implement speaker diarization for detailed insights.  
3. **UI/UX Improvements**: Add a user-friendly interface using frameworks like Streamlit or Flask.  
4. **Data Export**: Save meeting notes as PDF or TXT files.  

---

## **Contributing**  
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your changes.  

---

## **License**  
This project is licensed under the MIT License. See the `LICENSE` file for more details.  
---
