# Roman-Urdu-Medical-LLM
A medical chatbot for symptoms analysis and general medical advice.
## Saved Models:
The three fine-tuned models were saved to hugging face for easier access:
1. [Llama-1B](https://huggingface.co/farazahmad2004/NLP-Medical-Chatbot-Llama-1B)
2. [Llama-3B](https://huggingface.co/farazahmad2004/NLP-Medical-Chatbot-Llama-3B)
3. [Qwen-7B](https://huggingface.co/farazahmad2004/NLP-Medical-Chatbot-Qwen-7B)
## Requirements:
For requirements, makes sure to install all the libraries that are in **Setup** Cell of the notebooks, mainly:
- unsloth
- sentence-transformers
- langchain
- transformers
- evaluate
- bert_score

**Note:** This list is not comprehensive.
Regarding running, we have an `app.py` file in `code` folder, that runs Llama-1B for testing, but for faster inference, higher RAM and a GPU will be required. Please refer to the outputs generated in the evaluation section of notebooks to see sample outputs.
