# Fine-tuning LLM-Mistral 7B Instruct

My goal was to increase accuracy of formulating questions generated from the book. For this purpose I fine-tuned Mistral 7B Instruct (LLM). 
As a result, the fine-tuned model created questions 4 times more accurate than the base model.

Main steps:
* Prepare a dataset
* Test Prompts
* Fine-tune the Mistral 7B Instruct Model (PEFT - LoRA)
* Evaluate fine-tuning model

Technology stack:
* Hugging Face Transformers (Mistral 7B Instruct)
* Llama Index (GPT-3.5-turbo)
* Torch, Pandas, Google Colab
* Evaluate (Rouge)
