<div align="center">
  <h1>🗣️ First Steps in Large Language Models</h1>
  <img width="468" alt="Picture1" src="https://github.com/raghadalsaif/AutoGraph/assets/107502187/b73bd729-89d9-463c-b6ab-2e63bbfc85ca">
</div>


This file will contain your initial steps towards understanding Large Language Models (LLMs), including:

- LLM APIs
- Open source LLMs
- Prompt engineering(prompting guidelines to generate more specific and realistic outputs.)
- Structured output
- AutoGraph project

## File Overview:
- **"OpenAI API":** This file will contain a chat with the OpenAI API.
- **"Open Source LLM":** This file will utilize OLLAMA for prompt engineering.
- **"AutoGraph":** This will be a small project that takes user input such as text, articles, or research papers, and converts it into a JSON file structure for presentation.

# Solution Concept
"AutoGraph" will be a small project that takes user input (e.g., text, articles, research papers) and converts it into a prestaion in structured JSON file.

# Technologies & Tools 🛠️
- Jupyter Lab
- OLLAMA
- NLTK
- OpenAI API

# Developers 👩🏼‍💻
- [RAGHAD ALSAIF](https://github.com/raghadalsaif)

<div align="center">
  <h1>#AutoGraph project</h1>
  <img width="733" alt="Screenshot" src="https://github.com/raghadalsaif/AutoGraph/assets/107502187/510bac12-de9a-49e1-8afb-70ddb76fc431">
</div>

# Solution Concept
"AutoGraph" will be a small project that takes user input (e.g., text, articles, research papers) and converts it into a presentation in a structured JSON file.

# Technologies & Tools 🛠️
- Jupyter Lab
- OLLAMA
- NLTK
- OpenAI API

# Project Pipeline
AutoGraph pipeline consists of three primary stages: 
- Data pre-processing,
- Modeling,
- Output generation.

<div align="center">
  <img width="268" alt="Project Pipeline" src="https://github.com/raghadalsaif/AutoGraph/assets/107502187/4c663d4d-8e68-4f88-9a87-bb1e0a1a47be">
</div>

Data Extraction: This initial step involves extracting data from users, which can be achieved through either file uploads or direct text input.

Pre-processing:
- Lowercasing: Convert all text to lowercase to ensure uniformity.
- Tokenization: Break down the text into individual tokens (words or phrases) for further analysis.
- Punctuation Removal: Remove punctuation marks to focus solely on the textual content.
- Stopword Removal: Eliminate common words (such as "and," "the," "is") that do not contribute significant meaning to the text.
- Special Character Handling: Address any special characters present in the text.
- Lemmatization: Reduce words to their base or dictionary form to standardize variations.
- Spell Checking: Verify and correct spelling errors to enhance the accuracy of the text.

Modeling Phase: Once the data has undergone pre-processing, it moves on to the modeling phase for further analysis and interpretation.


Challenges Encountered:
- Processing Time: Operating on a single laptop without GPU support, the processing time for generating output is approximately 10 minutes per request, impacting efficiency.
- Input Limitation: While Llama3 accommodates a larger number of tokens per request compared to other models, it still faces constraints in handling input volume, limiting the scope of processed data.
- Model Hallucinations: The model occasionally generates content that does not exist in reality, necessitating prompt refinement and additional strategies to mitigate this issue.

# Future Pipeline
As AutoGraph expands, it's crucial that our Language Models (LLMs) become more domain-specific and generate outputs that are not just accurate but also contextually relevant to users. We've been exploring ways to enhance the model to cater to diverse domains. For instance, if a user inputs a technical article, the output should reflect more technical concepts, possibly even including code snippets. Similarly, if the text pertains to business, it should emphasize business-related aspects to enhance user satisfaction. We're extending this approach to other domains like marketing, health, and beyond.

To achieve this, we've conceived a second pipeline: the domain-specific pipeline. Once the user input undergoes preprocessing, the model will determine which domain(s) the text belongs to—be it tech, business, health, and so forth. Then, we'll employ fine-tuning to different LLMs to excel in each specific domain. This targeted approach ensures that the output aligns closely with the user's expectations, fostering trust in AutoGraph's capabilities.

<div align="center">
  <img width="468" alt="Future Pipeline" src="https://github.com/raghadalsaif/AutoGraph/assets/107502187/fe1d7ed3-f5ae-4505-8d05-ead7b5a2e184">
</div>






