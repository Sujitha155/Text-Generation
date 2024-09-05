# Text-Generation

This repository showcases a simple implementation of GPT-2 for text generation using Hugging Face's transformers library. The model generates text based on a given prompt, employing beam search to enhance the diversity and coherence of the generated content.

# Features

# Pre-trained Model: 

   Utilizes the GPT-2 model from Hugging Face for generating human-like text.
   
# Text Generation: 
   
   Produces coherent and contextually relevant text continuations based on an input prompt.
   
# Beam Search: 
   
   Uses beam search to explore multiple possibilities and improve the quality of the generated text.
   
# Installation

To use the code, install the required Python libraries:

pip install transformers torch

# Usage

# 1.Load Model and Tokenizer: 

  The script loads a pre-trained GPT-2 model and tokenizer.
  
# 2.Generate Text: 

  Input a text prompt to generate a continuation. The generation process includes parameters such as maximum length of the generated text and the number of beams for beam search.

# Parameters

• Prompt: The initial text input for the model to generate text from.

• Max Length: The maximum length of the generated sequence.

• Num Beams: Number of beams used in beam search to generate diverse outputs.

• No Repeat N-Gram Size: Prevents the repetition of n-grams to enhance text coherence.

# Example Output

The model can generate various types of content based on the input prompt.

# Requirements

# • transformers: 

Hugging Face's library for state-of-the-art NLP models.

# • torch: 

PyTorch library for tensor computations.

