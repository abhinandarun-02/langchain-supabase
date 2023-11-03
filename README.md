# Langchain Supabase Setup

This Python notebook outlines the setup and usage of the Langchain system with Supabase for embedding and searching textual data.

## Installation

To set up the Langchain and Supabase integration, follow these installation steps:

### 1. Create a Python Virtual Environment

On Linux or macOS:

```shell
python -m venv venv
source venv/bin/activate
```

On Windows:

```shell
python -m venv venv
venv\Scripts\activate
```

### 2. Install Dependencies
Install the necessary Python libraries using pip. These dependencies are crucial for the Langchain and Supabase integration to work correctly:

```shell
pip install -r requirements.txt
```

### 3. Configuration
Create a .env file in your project directory and populate it with your Supabase API URL and service key:

```
SUPABASE_URL=https://your-supabase-api-url.com
SUPABASE_SERVICE_KEY=your-service-key
```