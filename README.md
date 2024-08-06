# Research Paper Agents with RAG and LangChain

Welcome to the Research Paper Agents project! This repository contains code and resources for developing research agents using Retrieval-Augmented Generation (RAG) and LangChain.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Git

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/adrienbeyk/Research-Paper-Agents-RAG.git
   cd Research-Paper-Agents-RAG

2. **Install Dependencies**:
```pip install -r requirements.txt```

### Running the Notebook

1. **Navigate to the Directory**:
   ```bash
   cd ~/Documents/Code/Practice/crewai-rag-langchain/research-agents-rag

2. **Launch Jupyter Notebook**:
   ```jupyter notebook

3. **Open and Run the Notebook**:
Open Research-Paper-Agents-RAG.ipynb in the Jupyter Notebook interface and run the cells to execute the code.


### ## Libraries Used

Here are the main libraries used in this project and their purposes:

Here are the main libraries used in this project and their purposes:

- **dotenv**: Loads environment variables from a `.env` file.
- **langchain_community.document_loaders.PyPDFLoader**: Loads PDF documents for processing.
- **langchain.text_splitter.RecursiveCharacterTextSplitter**: Splits text into smaller chunks.
- **langchain_openai.OpenAIEmbeddings**: Generates embeddings using OpenAI's models.
- **langchain_openai.ChatOpenAI**: Interacts with OpenAI's chat models.
- **langchain.vectorstores.Qdrant**: Stores and queries vectors in Qdrant.
- **langchain.hub**: Accesses community-contributed resources.
- **langchain.chains.RetrievalQA**: Creates retrieval-based question-answering chains.
- **langchain.prompts.ChatPromptTemplate**: Creates chat prompts.
- **langchain.callbacks.StdOutCallbackHandler**: Handles standard output callbacks.
- **qdrant_client.QdrantClient**: Interacts with the Qdrant vector database.
- **qdrant_client.models.Distance**: Defines the distance metric for vector similarity.
- **qdrant_client.models.VectorParams**: Specifies parameters for vectors.
- **qdrant_client.models.PointStruct**: Defines the structure of points in the vector database.
- **crewai.Agent**: Creates agents in the Crew AI framework.
- **crewai.Task**: Defines tasks for agents in the Crew AI framework.
- **crewai.Crew**: Manages a collection of agents in the Crew AI framework.
- **crewai_tools.BaseTool**: Provides base functionality for tools in the Crew AI framework.
