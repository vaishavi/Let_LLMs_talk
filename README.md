# Let the LLMs Talk: Replication Project

This repository contains our course project for the "Natural Language Processing" class at George Washington University. Our project replicates the study by Abbasiantaeb et al., titled "Let the LLMs Talk: Simulating Human-to-Human Conversational QA via Zero-Shot LLM-to-LLM Interactions." We explored conversational question-answering (CQA) using two instances of pre-trained large language models (LLaMA3 and GPT4-Turbo) in the roles of a student and a teacher.

## Project Overview

- **Objective**: To simulate human-like conversational dynamics in an educational setting using a zero-shot learning approach.
- **Methodology**: Utilized two LLMs to autonomously generate and answer questions, aiming to sustain realistic dialogues and analyze their potential in educational and customer service applications.
- **Key Findings**: Our results underscore the need for additional training to enhance consistency and ensure completeness in responses, with GPT-4 demonstrating more effective performance than LLaMA3.

## Technologies Used

- **Programming Languages**: Python
- **Libraries**: nltk, re, openai, replicate
- **APIs**: OpenAI for GPT-4-turbo, Replicate for LLaMA3

## Setup and Installation
 Clone the repository:
  git clone https://github.com/yourusername/let-the-llms-talk.git
  cd let-the-llms-talk

 Install dependencies:
 pip install -r requirements.txt

 Environment Variables:
 Set up your OPENAI_API_KEY and REPLICATE_API_KEY in your environment variables or a .env file.

 Running the simulations:
 python src/simulate.py

## Contributing
We welcome contributions to this project! If you have suggestions or improvements, please fork the repository and submit a pull request.

## Authors
Vaishavi Vijayakandan
Kalyani Vinayagam Sivasundari
Aarifah Ullah

## Acknowledgments
Thanks to Zahra Abbasiantaeb and collaborators for their original research which inspired this replication study.
Gratitude to our professor and peers at George Washington University for their guidance and feedback.
