# AIMS_Intern_Assignment: Vision-Language Models for Recipe Generation

## Overview
This project explores the application of Vision-Language Models (VLMs) to generate cooking instructions from food images and noisy titles. The task focuses on leveraging multimodal AI capabilities to bridge the gap between visual understanding and natural language generation in the culinary domain.

## Project Structure
```
AIMS_Intern_Assignment/
├── Input-Files/
│   ├── Train.json
│   ├── Test.json
│   └── Images/
├── HuggingFace Model/
│   ├── notebook1.ipynb
│   └── notebook2.ipynb
└── Gemini Model/
    ├── VLM_Assignment.ipynb
    └── generated_output.json
```

## Key Features
- Multimodal recipe generation from images and titles
- Implementation of multiple VLM approaches
- Comprehensive evaluation using BLEU and ROUGE metrics
- State-of-the-art performance with Gemini 2.0

## Implementation Details

### 1. HuggingFace Attempt
- Initial implementation using BLIP2 model
- Two different approaches attempted:
  - Notebook 1: Achieved BLEU score of 0.0129
  - Notebook 2: Alternative implementation (under development)

### 2. Gemini Model Implementation
- Final implementation using Gemini 2.0 multimodal VLM
- Achieved impressive metrics:
  - BLEU Score: 0.0461
  - ROUGE-1 F1: 0.4650
  - ROUGE-2 F1: 0.1612
  - ROUGE-L F1: 0.2910

## Results
The Gemini 2.0 implementation shows promising results, with metrics comparable to state-of-the-art models in the field. The ROUGE-1 score of 0.4650 indicates strong semantic similarity between generated and reference recipes.

## Future Work
- Improve BLIP2 implementation in Notebook 2
- Experiment with different prompt engineering strategies
- Explore additional evaluation metrics
- Fine-tune models for better performance

## Requirements
- Python 
- Google Generative AI (Gemini)
- HuggingFace Transformers
- NLTK
- ROUGE Score
- PIL (Python Imaging Library)

## Installation
```bash
pip install google-generativeai
pip install transformers
pip install nltk
pip install rouge-score
pip install Pillow
```

## Usage
1. Clone the repository
2. Install required dependencies
3. Set up your API keys for Gemini
4. Run the Gemini_Model/VLM_Assignment.ipynb (for final implementation)

## License
MIT License 

## Acknowledgments
- Google Gemini Team for the multimodal VLM
- HuggingFace for the BLIP2 model
- AIMS for the internship opportunity 
