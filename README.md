# Medical-Chatbot

How to run?

### Clone the repository

```
git clone https://github.com/patelshehbaz/Medical-Chatbot.git
```

### Step 1: Create a conda environment

```
conda create -p medicalbot python=3.8 -y
```

```
conda activate medicalbot
```

### Step 2: Install the requirements

```
pip install -r requirements.txt
```

### Create a .env file in the root directory and add your Pinecone credentials as follows:

```
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```
