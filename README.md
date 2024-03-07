### Prerequisites
- **Jupyter notebook**,
- **Pinecone Account**: Sign up at [Pinecone.io](https://www.pinecone.io/).
).

### Setup Instructions

#### Step 1: Clone the Repository
Clone the SRH-CHATBOT-V3 repository to your local machine using the command:
```bash
git clone https://github.com/naveen987/Privacy-case-study.git
```

#### Step 2: Set Up Environment Variables
Create a `.env` file in the root directory and add your Pinecone credentials and Bing Search API key:
```ini
PINECONE_API_KEY = "your_pinecone_api_key_here"
PINECONE_API_ENV = "your_pinecone_environment_here"
```

#### Step 3: Download and Set Up the Model
Download the Llama 2 Model llama-2-13b-chat.ggmlv3.q4_0.bin from [Hugging Face](https://huggingface.co/TheBloke/Llama-2-13B-chat-GGML/blob/main/llama-2-13b-chat.ggmlv3.q4_0.bin) and place it in the model directory.

