# Embed_activations_inGPT2
This is a mechanistic interpretability project. Looking for distance in embedding space propagating through activations of LLMs

The project was submitted for Neel Nanda's 2024 stream. 
The document explaining the state of the project at the submission stage can be found @ https://docs.google.com/document/d/1PubUC7QuTd_oqmKEgx2AUxr5bGFD1tKHtrLUsgVofSo/edit

TLDR: I tried to find metrics, that could be applied to activations of LLMs, that would capture the concept of "closeness in embedding space" or, more prosaically "closeness in semantic meaning". 
I found that Shanon entropy of softmax of the difference of residual streams of prompts with two conceptually close tokens, show some weak signal in the last attention layer. Yet this signal was not very consistent and rather noisy and I could not find any features in the attention heads. 

State of the project as of 29.04.2024 - on pause, worth revisiting. 
