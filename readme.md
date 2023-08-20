# PDFChat Plus App

## Overview
------------
PDFChat Plus is an innovative Python utility designed for interactive conversations with an array of PDF documents. Engage in conversational inquiries using everyday language, and witness the tool respond intelligently by leveraging the content of the PDFs. Employing advanced language modeling, the application formulates accurate responses, provided your queries pertain to the uploaded PDFs.

## Operational Method
------------

The application orchestrates the following sequence to furnish responses to your inquiries:

1. PDF Ingestion: The tool ingests multiple PDF files, siphoning their textual essence.

2. Text Segmentation: Extracted text is partitioned into digestible units for streamlined processing.

3. Language Framework: The software harnesses a potent language model to generate textual embeddings for the segmented content.

4. Semantics Mapping: Upon submitting a query, the app juxtaposes it with text fragments, identifying the most contextually congruent units.

5. Response Generation: The chosen text units are fed into the language model, which formulates a response grounded in pertinent PDF content.

## Prerequisites and Setup
----------------------------
For PDFChat Plus installation, adhere to the subsequent directives:

1. Duplicate the repository onto your local apparatus.

2. Execute the ensuing command to satisfy prerequisite dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Obtain a secure API key from OpenAI and inject it into the project environment.
```commandline
OPENAI_API_KEY=your_secret_api_key
```
4. Also obtain a API key from HuggingFace and inject it into the project enviroment.
```commandline
HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_key
```

## Operating Instructions
-----
Operationalize PDFChat Plus as follows:

1. Confirm prerequisites are satisfied and the OpenAI API key is integrated into the environment.

2. Launch the `app.py` file via Streamlit CLI. Deploy the subsequent command:
   ```
   streamlit run app.py
   ```

3. The application materializes within your default web browser, showcasing the user-friendly interface.

4. Incorporate a multitude of PDF files using the designated instructions.

5. Employ the chat interface to vocally probe the loaded PDFs, seamlessly communicating in natural language.

## Collaboration
------------
This repository operates as an educational asset, unopen to further collaborative input. It stands as a supplementary resource for a pdf chatbot development. You are at liberty to exploit and augment the application as per your own requisites.

## License
-------
The MultiPDF Chat App is released under the [MIT License](https://opensource.org/licenses/MIT).
