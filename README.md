# RAGchatbot_Supabase_OpenAI

## Project Description

RAGchatbot_Supabase_OpenAI is a Retrieval-Augmented Generation (RAG) chatbot designed to answer questions about any customized topic of interest (at the moment is tailored for frontend engineering, web development, and JavaScript). The chatbot leverages OpenAI's GPT-4o model and Supabase for vector storage. It processes MDX files containing additional knowledge and uses them to provide accurate and contextually relevant answers.

## Features

- Load and process MDX files for additional knowledge.
- Use OpenAI's GPT-4o model for generating responses.
- Store and retrieve document vector embeddings using Supabase.
- Split large texts into manageable chunks for efficient processing.

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Supabase account and API keys
- OpenAI account and API keys

** The OpenAI key cannot be used for free, except for eligible new users who may receive a limited amount of credits. **

### Install Required Packages

```bash
pip install openai langchain langchain_community supabase

```

## Usage

create `.env` file to save OpenAPI key, supabase_url and supabase_key with your actual OpenAI, Supabase URL and key.

## Load MDX Files

Load all MDX files to the `docs` folder for processing.

## AI Chat

Chatbot role is catered towards frontend engineering as an example. It could be edited to suit any other topic of interest.

- It is working without a front-end at the moment.
