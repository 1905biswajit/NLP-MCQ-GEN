# MCQ Questions and Answers Generator

## Overview

The MCQ Questions and Answers Generator is an advanced tool designed to automate the creation of high-quality multiple-choice questions (MCQs) from any given text. Leveraging state-of-the-art natural language processing (NLP) techniques and machine learning models, this system extracts relevant keywords and generates challenging, contextually accurate questions and plausible distractors. This project aims to save time for educators while ensuring consistency and accuracy in assessment materials.

## Features

- **Automated Keyword Extraction**: Uses Python Keyphrase Extraction (PKE) to identify the most important keywords from the text.
- **Sentence Tokenization**: Splits the text into sentences and selects those suitable for question generation.
- **Sense Disambiguation**: Determines the correct sense of each keyword to ensure contextual accuracy.
- **Distractor Generation**: Utilizes WordNet and ConceptNet to create plausible distractors that match the sense of the keywords.
- **User-Friendly Interface**: Deployed using Streamlit, allowing users to upload text files and specify the number of MCQs to generate.
- **Customizable Output**: Generates MCQs tailored to the input text, providing educators with high-quality assessment tools.

## Future Enhancements

- **Advanced NLP Techniques**: Incorporating models like BERT and GPT for improved accuracy in keyword extraction and sense disambiguation.
- **Deeper Contextual Analysis**: Ensuring that distractors are more closely aligned with the intended meaning of the keywords.
- **User Feedback Mechanism**: Adding features for users to rate the quality of the generated MCQs to refine the algorithm over time.
- **Multilingual Support**: Expanding the system to support multiple languages, making it accessible to a broader audience.
- **Additional Question Types**: Exploring the generation of True/False questions to diversify assessment materials.
- **Enhanced Input Flexibility**: Supporting various input formats such as PowerPoint presentations, PDFs, images, and webpage links.

## Project Structure

```
MCQ-Generator/
│
├── data/
│   ├── sample_texts/
│   │   └── sample1.txt
│   │   └── sample2.txt
│   └── generated_mcqs/
│       └── sample_mcqs.txt
│
├── src/
│   ├── keyword_extraction.py
│   ├── sentence_tokenization.py
│   ├── sense_disambiguation.py
│   ├── distractor_generation.py
│   └── mcq_generation.py
│
├── app.py
│
├── requirements.txt
│
└── README.md
```

## Installation

To get started with the MCQ Questions and Answers Generator, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/MCQ-Generator.git
   cd MCQ-Generator
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. Open your web browser and go to `http://localhost:8501`.
2. Upload a text file containing the article or content from which you want to generate MCQs.
3. Specify the number of MCQs you wish to generate.
4. The system will process the input and display the generated MCQs along with the correct answers and distractors.

## Contribution

Contributions are welcome! If you have any suggestions for improvements or new features, feel free to create an issue or submit a pull request. Please ensure your contributions align with the project's goals and adhere to the coding standards.


## Acknowledgements

We would like to thank the developers of the libraries and tools that made this project possible, including Python, Streamlit, WordNet, ConceptNet, and the Python Keyphrase Extraction (PKE) library.

---

Feel free to customize this README content further to fit your project's specifics and personal preferences.
